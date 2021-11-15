<template>
  <ion-page>
    <ion-content fullscreen>
      <ion-list>
        <ion-list-header> My profile </ion-list-header>

        <ion-grid>
          <ion-row>
            <ion-col> </ion-col>

            <ion-col>
              <ion-avatar class="avt" slot="start">
                <img src="https://i.pravatar.cc/300" />
              </ion-avatar>
            </ion-col>

            <ion-col> </ion-col>
          </ion-row>
        </ion-grid>
      </ion-list>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonList,
  IonListHeader,
  IonAvatar,
  IonPage,
  IonContent,
  IonGrid,
  IonRow,
  IonCol
} from "@ionic/vue";

export default {
  name: "Tab3",
  components: { IonList, IonListHeader, IonAvatar, IonContent, IonPage, IonGrid, IonRow, IonCol },
};
</script>