<template>
<ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Subpage</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Subpage</ion-title>
        </ion-toolbar>
      </ion-header>
    
      <ion-button router-link="/subpage2">Subpage 2</ion-button>
    </ion-content>
</ion-page>
</template>

<script>
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonButton } from '@ionic/vue';

export default  {
  name: 'Tab2',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage, IonButton }
}
</script>

<style>

</style>