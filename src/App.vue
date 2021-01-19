<template>
  <v-app>
    <v-app-bar app>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </v-app-bar>
    <v-main>
      <v-container>
        <router-view />
      </v-container>
    </v-main>
  </v-app>
</template>
