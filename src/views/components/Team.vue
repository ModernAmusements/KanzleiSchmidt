<template>
  <section class="section section-shaped bg-secondary my-0 mb-lg overflow-hidden">
    <div class="shape shape-style-3">
      <span></span>
      <span></span>
      <span></span>
      <span></span>
    </div>
    <div class="container">
      <div class="row justify-content-center text-center mb-lg">
        <div class="col-lg-8">
          <h2 class="display-3">Rechtsanwälte</h2>
          <p class="lead text-muted">
            Rechtsanwälte der Kanzlei Schmidt-Blümel in München
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
          <div class="px-4">
            <img
              v-lazy="'img/theme/team-1-800x800.jpg'"
              class="rounded img-center img-fluid shadow shadow-lg--hover"
              style="width: 200px"
            />
            <div class="pt-4 text-center">
              <h5 class="title">
                <span class="d-block mb-1">Rechtsanwältin Elke Hubert</span>
                <small class="h6 text-muted">Erbrecht</small>
              </h5>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
          <div class="px-4">
            <img
              v-lazy="'img/theme/team-2-800x800.jpg'"
              class="rounded img-center img-fluid shadow shadow-lg--hover"
              style="width: 200px"
            />
            <div class="pt-4 text-center">
              <h5 class="title">
                <span class="d-block mb-1">Rechtsanwalt Schmidt-Blümel</span>
                <small class="h6 text-muted">Migrationsrecht</small>
              </h5>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
          <div class="px-4">
            <img
              v-lazy="'img/theme/team-3-800x800.jpg'"
              class="rounded img-center img-fluid shadow shadow-lg--hover"
              style="width: 200px"
            />
            <div class="pt-4 text-center">
              <h5 class="title">
                <span class="d-block mb-1">Rechtsanwalt Felix Lesner</span>
                <small class="h6 text-muted">Strafrecht</small>
              </h5>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
          <div class="px-4">
            <img
              v-lazy="'img/theme/team-4-800x800.jpg'"
              class="rounded img-center img-fluid shadow shadow-lg--hover"
              style="width: 200px"
            />
            <div class="pt-4 text-center">
              <h5 class="title">
                <span class="d-block mb-1">Rechtsanwältin Carolin Schmidt-Blümel</span>
                <small class="h6 text-muted">Migrationsrecht</small>
              </h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style></style>
