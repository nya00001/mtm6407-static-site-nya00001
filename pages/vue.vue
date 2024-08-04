<template>
    <v-container>
      <v-row align="center" justify="space-between" class="my-5">
        <v-col cols="12" md="6" class="text-center">
          <img src="~assets/img/vue-project.png" alt="Vue Project Screenshot" class="screenshot-image">
        </v-col>
        <v-col cols="12" md="6" class="text-center flex-column align-center">
          <p>
            Using what I learned about the Vue 3, Vue Router 4, Vite, and local storage I created a contact book web application, which allows a user to see and search through all contacts, add new contacts, and edit and delete existing contacts.
          </p>
          <v-btn class="vue-button" href="https://github.com/nya00001/contact-book" target="_blank">Check Project</v-btn>
        </v-col>
      </v-row>
    </v-container>
  </template>
  
  <script>
  export default {
  }
  </script>
  
  <style scoped>
  .screenshot-image {
    width: 100%;
    max-width: 500px;
    height: auto;
  }
  
  .text-center.flex-column.align-center {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  .vue-button {
    color: white;
    border: 1px solid white;
    border-radius: 5px;
    margin-top: 10px;
  }
  
  .vue-button:hover {
    background-color: white;
    color: black;
  }
  </style>
  