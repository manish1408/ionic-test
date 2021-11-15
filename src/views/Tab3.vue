<template>
<ion-header> 
    <ion-toolbar>
      <ion-title>My Profile</ion-title>
    </ion-toolbar>
</ion-header>
  <ion-page>

    <ion-content fullscreen>
      <ion-grid class="h-100">
        <ion-row class="h-100">
          <ion-col class="text-center">
            <div class="ion-margin-bottom">
              <img class="profile-picture" src="https://i.pravatar.cc/300" />
            </div>
            <ion-text class="secondary-clr"> id5 </ion-text>
            <ion-text> <h1>Helen Jobs</h1> </ion-text>
            <ion-text class="secondary-clr"> 19 yr </ion-text>
          </ion-col>
        </ion-row>
      </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonContent, IonGrid, IonRow, IonCol } from "@ionic/vue";

export default {
  name: "Tab3",
  components: { IonContent, IonPage, IonGrid, IonRow, IonCol },
};
</script>