<template>
  <v-app>
    <v-card>
      <v-app-bar
        color="blue lighten-2"
        flat
      >
        <v-app-bar-nav-icon />
        <v-toolbar-title>frayien</v-toolbar-title>
        <v-btn
          class="ml-5"
          to="/"
        >
          Home
        </v-btn>
        <v-btn
          class="ml-5"
          to="/about"
        >
          About
        </v-btn>
      </v-app-bar>
    </v-card>
      
    <router-view />
  </v-app>
</template>
