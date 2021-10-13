<template>
  <v-app>
    <v-app-bar 
      class="navbar"
      dense 
      elevate-on-scroll 
      flat
      color = "white"
    >
      <v-app-bar-title>
        <span class="nav-title">The CT</span>
      </v-app-bar-title>
    </v-app-bar>
    <v-main>
      <v-content>
        <!-- 
          This is where the page content goes 
          specified by the <Nuxt /> tag 
        -->
        <Nuxt />
      </v-content>
    </v-main>
    <!-- Footer goes here -->
  </v-app>
</template>
<!-- Below is the styling for everything in here -->

<style lang="scss">
  .v-toolbar{
    flex: 0.1;
  }
</style>