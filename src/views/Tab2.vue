<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Chats</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content fullscreen>
      <ion-list>
        <ion-item>
          <ion-avatar class="avt" slot="start">
            <img src="https://i.pravatar.cc/300" />
          </ion-avatar>
          <ion-label>
            <h2>Minsk</h2>
            <h3>Bob says hi</h3>
            <ion-badge class="slider-message" color="danger">2</ion-badge>
          </ion-label>
        </ion-item>

        <ion-item>
          <ion-avatar class="avt" slot="start">
            <img src="https://i.pravatar.cc/300" />
          </ion-avatar>
          <ion-label>
            <h2>Moscow</h2>
            <h3>I'm a big deal</h3>
          </ion-label>
        </ion-item>

        <ion-item>
          <ion-avatar class="avt" slot="start">
            <img src="https://i.pravatar.cc/300" />
          </ion-avatar>
          <ion-label>
            <h2>Kiev</h2>
            <h3>I'm a big deal</h3>
          </ion-label>
        </ion-item>
      </ion-list>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonList,
  IonLabel,
  IonItem,
  IonAvatar,
  IonPage,
  IonContent,
  IonBadge,
} from "@ionic/vue";

export default {
  name: "Tab2",
  components: {
    IonList,
    IonLabel,
    IonItem,
    IonAvatar,
    IonContent,
    IonPage,
    IonBadge,
  },
};
</script>