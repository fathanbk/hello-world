<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Author Biography</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true" >
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 1</ion-title>
        </ion-toolbar>
      </ion-header>
      <img src="../../resources/Pasfoto.jpeg" width =200>
      <p>Nama       : Fathan Bainal Kaffi</p>
      <p>NIM        : 1313621037</p> 
      <p>Prodi      : Ilmu Komputer</p>
      <p>Universitas: Universitas Negeri Jakarta</p>
      <p>Umur       : 20 Tahun</p> 
      <p>Tahun/Tanggal Lahir : 18/08/2003</p>
      <p>Alamat     : Jl. Kebon Jeruk Raya no.15 RT/RW 01/03, Sukabumi Utara, Jakarta Barat, DKI Jakarta</p>
     
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';


export default  defineComponent({
  name: 'Tab1Page',
  components: {  IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
