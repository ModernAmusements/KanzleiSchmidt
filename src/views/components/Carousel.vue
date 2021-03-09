<template>
    <section class="section section-lg section-shaped overflow-hidden my-0">
        <div class="shape shape-style-1 shape-default shape-skew">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
        </div>
        <div class="container py-0 pb-lg">
            <div class="row justify-content-between align-items-center">
                <div class="col-lg-5 mb-5 mb-lg-0">
                    <h1 class="font-weight-light">BR2Law</h1>
                    <p class="lead mt-4">Im Migrationsrecht und im Familienrecht sind wir aufgrund langjähriger Erfahrung und erfolgreich absolvierten Fachanwaltslehrgängen spezialisiert.
                        In den häufigen Schnittstellen zwischen Familienrecht und Migrationsrecht arbeiten wir eng zusammen und ergänzen uns.</p>
                    <a href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
                       class="btn btn-white mt-4">Mehr erfahren</a>
                </div>
                <div class="col-lg-6 mb-lg-auto">
                    <div class="rounded shadow-lg overflow-hidden transform-perspective-right">
                        <b-carousel id="carousel1"
                                    controls
                                    indicators>
                            <!-- Text slides with image -->
                            <!-- <b-carousel-slide img-src="img/theme/about-us.jpg"></b-carousel-slide> -->
                            <b-carousel-slide img-src="img/theme/k3.png"></b-carousel-slide>
                            <b-carousel-slide img-src="img/theme/k4.png"></b-carousel-slide>
                            <b-carousel-slide img-src="img/theme/k1.png"></b-carousel-slide>
                            <b-carousel-slide img-src="img/theme/k2.png"></b-carousel-slide>
                            <!-- <b-carousel-slide img-src="img/theme/get-in-touch.jpg"></b-carousel-slide> -->
                        </b-carousel>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
  components: {
    BCarousel,
    BCarouselSlide
  }
};
</script>
<style>
</style>
