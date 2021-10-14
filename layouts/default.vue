<template>
  <v-app>
    <!-- 
      Below is the top navigation bar. Will integrate mobile
      view later
     -->
    <v-app-bar 
      class="navbar"
      elevate-on-scroll 
      flat
      color = "white"
    >
      <v-app-bar-title><!-- app-bar-title is the left text -->
        <span class="nav-title">TCT</span>
      </v-app-bar-title>
      <v-spacer></v-spacer><!-- Middle -->
      <div class="nav-link-container">
      <nuxt-link to="/" class="nav-link">Home</nuxt-link>
      <nuxt-link to="/" class="nav-link">About</nuxt-link>
      <nuxt-link to="/" class="nav-link">Episodes</nuxt-link>
      <nuxt-link to="/" class="nav-link">Contact us</nuxt-link>
      </div>
      <v-spacer></v-spacer> <!-- Right -->
      <div class="login-button-container">
      <nuxt-link to="/" class="login-button">Login</nuxt-link>
      </div>
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
    <!-- 
      Footer will eventually go here. This is one of the
      last priorities though
     -->
  </v-app>
</template>
<!-- Below is the styling for everything in here -->

<style lang="scss">
  .v-toolbar{
    flex: 0.1;
  }
  .navbar{
    .nav-title{
      text-overflow: unset;
    }
    .nav-link{
      text-decoration: none;
      color: black;
      margin-right: 22px;
      :last-child{
        margin-right: 0;
      }
    }
    .login-button-container{
      .login-button{
        color: white;
        background-color: #0075FF;
        padding: 10px;
        text-decoration: none;
        padding-right: 30px;
        padding-left: 30px;
      }
    }
    
  }
</style>