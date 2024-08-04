<template>
    <v-container>
      <v-row align="center" justify="space-between" class="my-5">
        <v-col cols="12" md="6" class="text-center">
          <img src="~assets/img/capstone-project.png" alt="Capstone Project Screenshot" class="screenshot-image">
        </v-col>
        <v-col cols="12" md="6" class="text-center flex-column align-center">
          <p>
            A capstone project is designed to test a cumulation of skills by creating a real-world project. Using the skills I have learned from Web Development I, II, and III, Using the QuizAPI, I designed and developed a web application that will display a random quiz question upon the user's request. When the user submits an answer they are informed if the selected answer was correct. The web application will keep track of the number of correct and incorrect answers.
            The project requires working with HTML, CSS, and JavaScript to create a responsive and dynamic website and requires deliverables including a mockup, a static prototype, and a final product.
          </p>
          <v-btn class="js-button" href="https://github.com/nya00001/mtm6302-capstone-nya00001/tree/part-4" target="_blank">Check Project</v-btn>
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
    max-width: 800px;
    height: auto;
  }
  
  .text-center.flex-column.align-center {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  .js-button {
    color: white;
    border: 1px solid white;
    border-radius: 5px;
    margin-top: 10px;
  }
  
  .js-button:hover {
    background-color: white;
    color: black;
  }
  </style>
  