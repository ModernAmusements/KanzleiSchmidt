<template>
    <div>
        <hero></hero>
        <carousel></carousel>
        <cards></cards>
        <icons></icons>
        <team></team>
        <cta></cta>
          <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt-lg pb-300">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h2 class="display-3 text-white">Anmeldeformular</h2>
                        <p class="lead text-white">Dieses Formular dient zur Bestätigung eines vereinbarten Termins und zur Erfassung Ihrer Kontaktdaten. Die Daten werden vertraulich und entsprechend der EU-Datenschutzgrundverordnung (DSGVO) behandelt.</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-lg-0 section-contact-us">
            <div class="container">
                <div class="row justify-content-center mt--300">
                    <div class="col-lg-8">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Besteht Anspruch auf Beratungshilfe?</h4>
                            <p class="mt-0">Besteht Anspruch auf Beratungshilfe, erhalten Sie bei dem Amtsgericht, in dessen Bezirk Ihr Wohnort liegt, einen Berechtigungsschein.</p>
                            <base-input class="mt-5"
                                        alternative
                                        placeholder="Ihr Name"
                                        addon-left-icon="ni ni-user-run">
                            </base-input>
                            <base-input alternative
                                        placeholder="Ihre Email-Addresse"
                                        addon-left-icon="ni ni-email-83">
                            </base-input>
                            <base-input class="mb-4">
                                    <textarea class="form-control form-control-alternative" name="name" rows="4"
                                              cols="80" placeholder="Anliegen...."></textarea>
                            </base-input>
                            <base-button type="default" round block size="lg">
                                Nachricht Senden
                            </base-button>
                        </card>
                    </div>
                </div>
            </div>
        </section>
        <!-- <basic-elements></basic-elements>
        <inputs></inputs>
        <custom-controls></custom-controls>
        <navigation></navigation>
        <javascript-components></javascript-components>
        <examples></examples>
        <download-section></download-section> -->
    </div>
</template>
<script>
import Hero from "./components/Hero";
import Cards from "./components/Cards";
import Cta from "./components/Cta";
import Team from "./components/Team";
import BasicElements from "./components/BasicElements";
import Inputs from "./components/Inputs";
import CustomControls from "./components/CustomControls";
import Navigation from "./components/Navigation";
import JavascriptComponents from "./components/JavascriptComponents";
import Carousel from "./components/Carousel";
import Icons from "./components/Icons";
import Examples from "./components/Examples";
import DownloadSection from "./components/DownloadSection";

export default {
  name: "components",
  components: {
    Hero,
    Cards,
    Team,
    Cta,
    BasicElements,
    Inputs,
    CustomControls,
    Navigation,
    JavascriptComponents,
    Carousel,
    Icons,
    Examples,
    DownloadSection
  }
};
</script>
