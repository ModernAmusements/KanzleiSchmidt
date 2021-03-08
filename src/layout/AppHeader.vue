<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <img src="img/brand/white.png" alt="logo">
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/">
                        <img src="img/brand/blue.png">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center lead ml-lg-auto">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <span class="lead nav-link-inner--text">Kanzlei</span>
                    </a>
                <base-dropdown tag="li" class="nav-item">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <span class="lead nav-link-inner--text">Rechtsgebiete</span>
                    </a>
                    <router-link to="/landing" class="dropdown-item">Migrationsrecht</router-link>
                    <router-link to="/profile" class="dropdown-item">Familienrecht</router-link>
                    <router-link to="/login" class="dropdown-item">Erbrecht</router-link>
                    <router-link to="/register" class="dropdown-item">Strafrecht</router-link>
                </base-dropdown>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
