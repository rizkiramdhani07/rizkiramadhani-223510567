<template>
  <q-layout>
    <navbar />
    <q-page-container>
      <carousel />
      <div class="q-pa-md">
        <q-card>
          <card />
        </q-card>
      </div>
    </q-page-container>
    <q-footer>
      <q-toolbar>
        <q-toolbar-title>
          © 2024 Rizki Store
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Carousel from './components/Carousel.vue'
import Card from './components/Card.vue'

export default {
  components: {
    Navbar,
    Carousel,
    Card,
  }
}
</script>