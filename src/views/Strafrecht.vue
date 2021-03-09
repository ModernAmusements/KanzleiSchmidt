<template>
  <div class="profile-page">
    <section
      class="section-profile-cover bg-gradient-default section-shaped my-0"
    ></section>
    <section class="section section-skew">
      <div class="container">
        <card shadow class="card-profile mt--300" no-body>
          <div class="px-4">
            <div class="row justify-content-center">
              <div class="col-lg-3 order-lg-2">
                <div class="card-profile-image">
                  <a href="#">
                    <img v-lazy="'img/theme/team-3-800x800.jpg'" class="rounded" />
                  </a>
                </div>
              </div>
              <div class="col-lg-4 order-lg-3 text-lg-right align-self-lg-center">
                <div class="card-profile-actions py-4 mt-lg-0">
                  <base-button type="outline" size="sm" class="mr-4">Kontakt</base-button>
                  <base-button type="default" size="sm" class="float-right"
                    >Nachricht</base-button
                  >
                </div>
              </div>
              <div class="col-lg-4 order-lg-1">
                <div class="card-profile-stats d-flex justify-content-center">
                  <div>
                    <span class="heading">2012</span>
                    <span class="description lead">Fachanwältin</span>
                  </div>
                  <div>
                    <span class="heading">2013</span>
                    <span class="description lead">Fachanwaltslehrgang</span>
                  </div>
                </div>
              </div>
            </div>
            <div class="text-center pt-100">
              <h3>
                Felix Lesner
                <span class="font-weight-light">, 32</span>
              </h3>
              <div class="h6 lead font-weight-300">
                <i class="ni location_pin mr-2"></i>München, Deutschland
              </div>
              <div class="h6 mt-4">
                <i class="ni business_briefcase-24 mr-2"></i>Strafrecht - Erbrecht
              </div>
              <div class="lead">
                <i class="ni education_hat mr-2"></i>Studium der Rechtswissenschaft an den
                Universitäten Saarbrücken und Bonn.<br />
                Seit 2014 fast ausschließlich im Migrationsrecht tätig.
              </div>
            </div>
            <div class="mt-5 py-5 border-top text-center">
              <div class="row justify-content-center">
                <div class="col-lg-9">
                  <p>
                    Rechtsanwalt Erbrecht München <br />
                    Rechtsanwaltskammer München Münchner Anwaltsverein im Deutschen
                    Anwaltsverein (DAV) Arbeitsgemeinschaft Migrationsrecht im DAV Beirat
                    der Refugee Law Clinic München
                  </p>
                  <a href="#">Mehr erfahren</a>
                </div>
              </div>
            </div>
          </div>
        </card>
      </div>
    </section>
    <sectionTwo></sectionTwo>
  </div>
</template>
<script>
import SectionTwo from "./components/SectionTwo";
export default {
  name: "components",
  components: {
    SectionTwo,
  },
};
</script>
<style></style>