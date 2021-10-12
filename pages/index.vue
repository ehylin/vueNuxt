<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card>
        <v-card-title class="headline">
          Bienvenidos Vuetify + Nuxt.js 
        </v-card-title>
          <v-card-title class="headline">
           Rick and Morty 
        </v-card-title>
      
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/personajes"
          >
           Ver personajes
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>
