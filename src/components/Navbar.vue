
<template>
    <div class="q-pa-md">
      <q-layout view="lHh lpr lFf" container style="height: 250px" class="shadow-2 rounded-borders">
        <q-header elevated class="bg-cyan">
          <q-toolbar>
            <q-avatar>
                <img src="../assets/rizkikeren.jpg">
            </q-avatar>
            <q-toolbar-title>Rizki Store</q-toolbar-title>
            <q-space />
          </q-toolbar>
        </q-header>
  
        <q-page-container>
          <q-page class="q-pa-md">
            <p v-for="n in 1" :key="n" class="promo-text">
              Ingin Menjadi Starboy? mampir kesiniiii!!
            </p>
          </q-page>
        </q-page-container>
      </q-layout>
    </div>
  </template>
  
  <script>
  export default {
    name: 'OnlineStoreBagas',
  };
  </script>
  
  <style>
  .promo-text {
    font-size: 40px;
    font-weight: bold;
    color: #161313; 
    text-align: center;
    margin: 20px 0;
    background-color: #f0f8ff; 
    padding: 10px; 
    border-radius: 10px; 
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); 
  }
  </style>
  