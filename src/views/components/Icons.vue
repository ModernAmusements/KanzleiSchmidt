<template>
    <section class="section section-lg section-nucleo-icons pb-250">
        <div class="container" @mouseleave="showIconsAnimation = false">
            <div class="row justify-content-center" @mouseover="showIconsAnimation = true">
                <div class="col-lg-8 text-center">
                    <h2 class="display-3">BR2LAW</h2>
                    <p class="lead">
                       Rechtsgebiete der Kanzlei Schmidt-Blümel in München. Die Kanzlei hat sich auf die folgenden Rechtsgebiete spezialisiert:
                    </p>
                    <div class="btn-wrapper">
                        <a href="https://demos.creative-tim.com/argon-design-system/docs/foundation/icons.html"
                           class="btn">Alle Rechtsgebiete</a>
                        <a href="https://nucleoapp.com/?ref=1712" target="_blank" class="btn btn-primary mt-3 mt-md-0">Spezialisiert</a>
                    </div>
                </div>
            </div>
            <div class="blur--hover">
                <a href="https://demos.creative-tim.com/argon-design-system/docs/foundation/icons.html">
                    <div class="icons-container blur-item mt-5" :class="{'on-screen': showIconsAnimation}">
                        <!-- Center -->
                        <i class="icon">
                        </i>
                        <!-- Right 1 -->
                        <i class="icon icon-sm ni ni-album-2"></i>
                        <i class="icon icon-sm ni ni-app"></i>
                        <i class="icon icon-sm ni ni-atom"></i>
                        <!-- Right 2 -->
                        <i class="icon ni ni-bag-17"></i>
                        <i class="icon ni ni-bell-55"></i>
                        <i class="icon ni ni-credit-card"></i>
                        <!-- Left 1 -->
                        <i class="icon icon-sm ni ni-briefcase-24"></i>
                        <i class="icon icon-sm ni ni-building"></i>
                        <i class="icon icon-sm ni ni-button-play"></i>
                        <!-- Left 2 -->
                        <i class="icon ni ni-calendar-grid-58"></i>
                        <i class="icon ni ni-camera-compact"></i>
                        <i class="icon ni ni-chart-bar-32"></i>
                    </div>
                    <span class="blur-hidden h5 ">Entdecken Sie unsere Rechtsgebiete</span>
                </a>
            </div>
        </div>
    </section>
</template>
<script>
export default {
  data() {
    return {
      showIconsAnimation: false
    };
  },
  methods: {
    onScroll(evt) {
      console.log(evt);
    }
  }
};
</script>
<style>
</style>
