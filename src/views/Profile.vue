<template>
  <div class="profile-page">
    <section class="section-profile-cover bg-gradient-default section-shaped my-0">
    </section>
    <section class="section section-skew">
      <div class="container">
        <card shadow class="card-profile mt--300" no-body>
          <div class="px-4">
            <div class="row justify-content-center">
              <div class="col-lg-3 order-lg-2">
                <div class="card-profile-image">
                  <a href="#">
                    <img v-lazy="'img/theme/team-4-800x800.jpg'" class="rounded" />
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
            <div class="text-center mt-5">
              <h3>
                Elke Hubert
                <span class="font-weight-light">, 27</span>
              </h3>
              <div class="h6 lead font-weight-300">
                <i class="ni location_pin mr-2"></i>München, Deutschland
              </div>
              <div class="h6 mt-4">
                <i class="ni business_briefcase-24 mr-2"></i>Familienrecht - Erbrecht
              </div>
              <div class="lead">
                <i class="ni education_hat mr-2"></i>Studium der Rechtswissenschaften an
                der Universität Erlangen-Nürnberg <br> und anschließendes 1.Staatsexamen mit
                Prädikat im Jahr 2001
              </div>
            </div>
            <div class="mt-5 py-5 border-top text-center">
              <div class="row justify-content-center">
                <div class="col-lg-9">
                  <p>
                    Rechtsanwalt Erbrecht München <br />
                    Nach der ersten Trauer über den Verlust eines Angehörigen oder nahe
                    stehenden Erblassers folgt im zweiten Schritt leider sehr häufig die
                    Auseinandersetzung der Hinterbliebenen über das Erbe. Am Ende geht es
                    - wie so oft - um das materielle Vermögen, das aufgeteilt wird. Sehr
                    viel Ärger und Probleme ließen sich vermeiden, wenn sich jeder
                    erwachsene Bürger mit Unterstützung eines spezialisierten Anwalts
                    Gedanken über seinen letzten Willen machen würde. Da der Tod in
                    unserer Kultur meist aus dem täglichen Leben ausgeblendet wird, sind
                    unwillkommene Überraschungen nach dem Tod fast unausweichlich. Nur
                    rund 20 Prozent der deutschen Bürger haben ein Testament! Für die
                    restlichen 80 Prozent gilt die gesetzliche Erbfolge. Und es spielt am
                    Ende keine Rolle, ob sie die Erbfolge kennen oder für gut befunden
                    hätten. Eigene letztwillige Verfügungen fallen nicht leicht. Gern
                    schiebt man die Regelung der Rechtsfolgen nach dem eigenen Ableben
                    immer wieder hinaus. Es ist auch uns bewusst, dass der gesamte Bereich
                    sehr sensibel zu behandeln ist - insbesondere wenn es neben der
                    Vermögensnachfolge um Altersvollmachten oder Patientenverfügung geht.
                    Umso mehr gehören auch die menschlichen Aspekte zu einer gründlichen
                    Beratung.
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
    SectionTwo
  }
};
</script>
<style></style>
