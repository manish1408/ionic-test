<template>
  <ion-page>
    <ion-content fullscreen>
      <ion-list>
        <ion-list-header> Chats </ion-list-header>

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
  IonListHeader,
  IonAvatar,
  IonPage,
  IonContent,
  IonBadge
} from "@ionic/vue";

export default {
  name: "Tab2",
  components: { IonList, IonLabel, IonItem, IonListHeader, IonAvatar, IonContent, IonPage, IonBadge},
};
</script>