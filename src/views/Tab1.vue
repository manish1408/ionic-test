<template>
  <ion-page>
    <ion-content class="ion-padding" scroll-y="false">
      <ion-slides pager="true" :options="slideOpts">
        <ion-slide>
          <div class="slide">
            <img src="assets/slider-1.svg" />
            <h2>Connect easily with your family and friends over countries</h2>
          </div>
        </ion-slide>

        <ion-slide>
          <div class="slide">
            <img src="assets/slider-1.svg" />
            <h2>Connect easily with your family and friends over countries</h2>
          </div>
        </ion-slide>

        <ion-slide>
          <div class="slide">
            <img src="assets/slider-1.svg" />
            <h2>Connect easily with your family and friends over countries</h2>
          </div>
        </ion-slide>

        <ion-slide>
          <div class="slide">
            <img src="assets/slider-1.svg" />
            <h2>Connect easily with your family and friends over countries</h2>
          </div>
        </ion-slide>
      </ion-slides>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonSlides, IonSlide, IonContent, IonPage } from "@ionic/vue";

export default {
  name: "Tab1",
  components: { IonSlides, IonSlide, IonContent, IonPage },
  setup() {
    const slideOpts = {
      initialSlide: 1,
      speed: 400,
    };
    return { slideOpts };
  },
};
</script>