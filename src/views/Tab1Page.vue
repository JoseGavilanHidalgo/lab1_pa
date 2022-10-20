<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Mensajes</ion-title>
      </ion-toolbar>
    </ion-header>
    
    <ion-content :fullscreen="true">
      <ion-searchbar color=""></ion-searchbar>
      <ion-card button="true" color="success">
        <ion-card-header>
          <img src="./personal_medico.png" class="img1"/>
          <ion-card-title class="nombre">Dra. María
          </ion-card-title>
            <ion-card-subtitle class="rol">Personal Medico
            </ion-card-subtitle>
            <br>
        </ion-card-header>
        <ion-card-content style="display:block">
            <p class="mensaje"> <time style="float:left;padding-right: 10px; ">11:25am</time>¿Como te has sentido hoy?  <ion-badge style="float:right" class="badges">3</ion-badge></p>
        </ion-card-content>
      </ion-card>

      <ion-card button="true" color="warning">
        <ion-card-header>
          <img src="./cuidador.png" class="img1"/>
          <ion-card-title class="nombre">Laura</ion-card-title>
            <ion-card-subtitle class="rol">Cuidador</ion-card-subtitle><br>
        </ion-card-header>
        <ion-card-content style="display:block">
            <p class="mensaje"> <time style="float:left;padding-right: 10px; ">11:25am</time>¿Como te has sentido hoy?  <ion-badge style="float:right" class="badges">3</ion-badge></p>
        </ion-card-content>
      </ion-card>

      <ion-card button="true" color="success">
        <ion-card-header>
          <img src="./personal_medico.png" class="img1"/>
          <ion-card-title class="nombre">Dr. Juan</ion-card-title>
            <ion-card-subtitle class="rol">Personal Medico</ion-card-subtitle>
            <br>
        </ion-card-header>
        <ion-card-content style="display:block">
            <p class="mensaje"> <time style="float:left;padding-right: 10px; ">11:25am</time>¿Como te has sentido hoy?  <ion-badge style="float:right" class="badges">3</ion-badge></p>
        </ion-card-content>
      </ion-card>

      <ion-card button="true" color="warning">
        <ion-card-header>
          <img src="./cuidador.png" class="img1"/>
          <ion-card-title class="nombre">Roberto</ion-card-title>
            <ion-card-subtitle class="rol">Cuidador</ion-card-subtitle><br>
        </ion-card-header>
        <ion-card-content style="display:block">
            <p class="mensaje"> <time style="float:left;padding-right: 10px; ">11:25am</time>¿Como te has sentido hoy?  <ion-badge style="float:right" class="badges">3</ion-badge></p>
        </ion-card-content>
      </ion-card>

      <ion-card button="true" color="success">
        <ion-card-header>
          <img src="./personal_medico.png" class="img1" />
          <ion-card-title class="nombre">Dr. Juan</ion-card-title>
            <ion-card-subtitle class="rol">Personal Medico</ion-card-subtitle><br>
        </ion-card-header>
        <ion-card-content style="display:block">
            <p class="mensaje"> <time style="float:left;padding-right: 10px; ">11:25am</time>¿Como te has sentido hoy?  <ion-badge style="float:right" class="badges">3</ion-badge></p>
        </ion-card-content>
      </ion-card>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {IonBadge, IonContent, IonHeader, IonPage, IonTitle, IonToolbar ,IonSearchbar} from '@ionic/vue';
import { defineComponent } from 'vue';
export default defineComponent({
  name: 'HomePage', 
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonTitle,
    IonBadge,
    IonSearchbar,
    IonToolbar,
  }
});
</script>


<style scoped>
#container {
  text-align: center;
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  color: #8c8c8c;
  margin: 0;
}

#container a {
  text-decoration: none;
}

.img1 {
  height: 80px;
  width: 100px;
  float:left;
  clear:left;
  margin-right: 20px;
}

.nombre{
  color:black;
}
.rol {
  color:black;
}

.mensaje {
  padding-top:5px;
}
</style>