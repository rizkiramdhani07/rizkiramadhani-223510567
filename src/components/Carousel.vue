<template>
    <div class="q-pa-md">
      <q-carousel
        animated
        v-model="slide"
        arrows
        navigation
        infinite
      >
        <q-carousel-slide :name="1" img-src="../assets/rizkikeren9.jpg" />
        <q-carousel-slide :name="2" img-src="../assets/rizkikeren5.jpg" />
        <q-carousel-slide :name="3" img-src="../assets/rizkikeren6.jpg" />
        <q-carousel-slide :name="4" img-src="../assets/rizkikeren7.jpg" />
      </q-carousel>
    </div>
  </template>
  
  <script>
  import { ref } from 'vue'
  
  export default {
    setup () {
      return {
        slide: ref(1)
      }
    }
  }
  </script>