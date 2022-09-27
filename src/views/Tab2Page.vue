<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Grade Record</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 2</ion-title>
        </ion-toolbar>
      </ion-header>
      <h4>Grade record saya dalam mata kuliah terkait pemrograman cukup bagus seperti pada matkul Dasar-Dasar Pemrograman dan Struktur Data dan Algoritma mendapat nilai A dan A-</h4>
      
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';


export default defineComponent({
  name: 'Tab2Page',
  components: {  IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
