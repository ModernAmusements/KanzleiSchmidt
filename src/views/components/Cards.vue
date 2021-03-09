<template>
  <section class="section section-shaped my-0 overflow-hidden">
    <div class="shape shape-style-3 bg-gradient-default shape-skew">
      <span></span>
      <span></span>
      <span></span>
      <span></span>
    </div>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-7 text-center">
          <h1 class="display-3 mt-4 text-white mb-5">
            Die Kanzlei hat sich auf die folgenden Rechtsgebiete spezialisiert:
          </h1>
        </div>
        <div class="col-lg-12">
          <div class="row row-grid">
            <div class="col-lg-4">
              <card class="border-0" hover shadow body-classes="py-5">
                <icon name="ni ni-check-bold" type="primary" rounded class="mb-4"> </icon>
                <h6 class="text-primary display-3 font-weight-bold">Migration</h6>
                <p class="description lead mt-3">
                  Staatsangehörigenrecht bzw. Einbürgerung, Asylrecht
                </p>
                <div>
                  <badge type="primary" rounded>Visum</badge>
                  <badge type="primary" rounded>Asylverfahren</badge>
                  <badge type="primary" rounded>Einbürgerung</badge>
                </div>
                <base-button tag="a" href="#" type="primary" class="mt-4">
                  Weiterlesen
                </base-button>
              </card>
            </div>
            <div class="col-lg-4">
              <card class="border-0" hover shadow body-classes="py-5">
                <icon name="ni ni-istanbul" type="primary" rounded class="mb-4"> </icon>
                <h6 class="text-primary display-3 font-weight-bold">Familienrecht</h6>
                <p class="description lead mt-3">
                  Typische familienrechtliche Angelegenheiten
                </p>
                <div>
                  <badge type="primary" rounded>Eheverträge</badge>
                  <badge type="primary" rounded>Ehescheidung</badge>
                  <badge type="primary" rounded>Unterhaltsfragen</badge>
                </div>
                <base-button tag="a" href="#" type="primary" class="mt-4">
                  Weiterlesen
                </base-button>
              </card>
            </div>
            <div class="col-lg-4">
              <card class="border-0" hover shadow body-classes="py-5">
                <icon name="ni ni-planet" type="primary" rounded class="mb-4"> </icon>
                <h6 class="text-primary display-3 font-weight-bold">Erbrecht</h6>
                <p class="description lead mt-3">Vielfältige Facetten des Erbrechts</p>
                <div>
                  <badge type="primary" rounded>Testamenten</badge>
                  <badge type="primary" rounded>Vertretung</badge>
                  <badge type="primary" rounded>Erbverträge</badge>
                </div>
                <base-button tag="a" href="#" type="primary" class="mt-4">
                  Weiterlesen
                </base-button>
              </card>
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
