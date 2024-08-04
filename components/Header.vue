<template>
    <v-app-bar app color="black" dark>
      <v-toolbar-title>
        <img src="~assets/img/logo.png" alt="logo" class="logo">
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn to="/" text class="white--text">Home</v-btn>
      <v-btn to="/php" text class="white--text">PHP</v-btn>
      <v-btn to="/javascript" text class="white--text">JavaScript</v-btn>
      <v-btn to="/react" text class="white--text">React</v-btn>
      <v-btn to="/vue" text class="white--text">Vue</v-btn>
    </v-app-bar>
  </template>
  
  <script>
  export default {
  }
  </script>
  
  <style scoped>
  .logo {
    height: 40px;
    animation: bounceIn 1.5s;
  }
  
  @keyframes bounceIn {
    0% {
      opacity: 0;
      transform: scale(0.3) translateY(-200px);
    }
    50% {
      opacity: 1;
      transform: scale(1.05) translateY(10px);
    }
    70% {
      transform: scale(0.9) translateY(-10px);
    }
    100% {
      transform: scale(1) translateY(0);
    }
  }
  </style>
  