<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar class="toolbar">
        <ion-title>Nosotros</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <ion-card class="container-nos">
        <ion-card-header>
          <ion-card-title class="container-nos_title"
            >Misión</ion-card-title
          >
        </ion-card-header>

        <ion-text>
          <p class="descripcion">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui oficia deserunt mollit anim id est laborum.</p>
        </ion-text>
      </ion-card>


       <ion-img
           src="/assets/img/nosotros/ffoc.png"
           class="img-nosotros"
       ></ion-img>


       <ion-card class="container-nos">
        <ion-card-header>
          <ion-card-title class="container-nos_title"
            >Visión</ion-card-title
          >
        </ion-card-header>

        <ion-text>
          <p class="descripcion">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui oficia deserunt mollit anim id est laborum.</p>
        </ion-text>
      </ion-card>

        <ion-img
           src="/assets/img/nosotros/starhome.png"
           class="img-nosotros"
       ></ion-img>
    </ion-content>

    
  </ion-page>
</template>

<script>
import {
  IonContent,
  IonHeader,
  IonPage,
  IonTitle,
  IonToolbar,
  IonImg
  } from "@ionic/vue";
import { defineComponent } from "vue";

export default defineComponent({
  name: "HomePage",
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonTitle,
    IonToolbar,
    IonImg
  },
  data(){
    
  }
});
</script>