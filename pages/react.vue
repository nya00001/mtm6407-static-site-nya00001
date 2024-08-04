<template>
    <v-container>
      <v-row align="center" justify="space-between" class="my-5">
        <v-col cols="12" md="6" class="text-center">
          <img src="~assets/img/t-shirts-project.png" alt="T-Shirts Project Screenshot" class="screenshot-image">
        </v-col>
        <v-col cols="12" md="6" class="text-center flex-column align-center">
          <p>
            Using the React framework I created a t-shirts storefront. Each t-shirt is displayed with the title, image, price, and the number of remaining stock. If the remaining stock is 0, then the term "Out of Stock" is displayed.
            A "buy" button and "quantity" select box appears for those t-shirts with a stock above 0.
            The select box allows the user to select the number of t-shirts to buy. The user cannot select more than the available stock, and clicking on the "buy" button should decrease the respective t-shirt's stock by the quantity selected.
          </p>
          <v-btn class="react-button" href="https://github.com/ac-imd/mtm6404-t-shirts-nya00001/tree/master" target="_blank">Check Project</v-btn>
        </v-col>
      </v-row>
  
      <v-row align="center" justify="space-between" class="my-5">
        <v-col cols="12" md="6" class="text-center">
          <img src="~assets/img/notifications-project.png" alt="Notifications Project Screenshot" class="screenshot-image">
        </v-col>
        <v-col cols="12" md="6" class="text-center flex-column align-center">
          <p>
            Using React and Vite, I created an application to display a list of notifications. The user should be able to clear individual notifications or all notifications. The web application displays all notifications and all notification data when the page loads. The number of notifications is displayed on the page.
            The user should be able to clear individual notifications. The user should be able to clear all notifications at once.
          </p>
          <v-btn class="react-button" href="https://github.com/nya00001/mtm6404-notifications" target="_blank">Check Project</v-btn>
        </v-col>
      </v-row>
  
      <v-row align="center" justify="space-between" class="my-5">
        <v-col cols="12" md="6" class="text-center">
          <img src="~assets/img/seuss-project.png" alt="Seuss Project Screenshot" class="screenshot-image">
        </v-col>
        <v-col cols="12" md="6" class="text-center flex-column align-center">
          <p>
            Using React, Vite, React Router, Fetch, and the Seussology API I created a simple books web application. The books page dynamically retrieves and displays the book cover images. Clicking on the book image will take the user to that book's detail page. The book's details page dynamically retrieves and displays the book's title, the book's cover image, and the book's description. The quotes page dynamically retrieves 10 random quotes and displays them on the page.
          </p>
          <v-btn class="react-button" href="https://github.com/ac-imd/mtm6404-seuss-treasury-nya00001" target="_blank">Check Project</v-btn>
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
  
  .react-button {
    color: white;
    border: 1px solid white;
    border-radius: 5px;
    margin-top: 10px;
  }
  
  .react-button:hover {
    background-color: white;
    color: black;
  }
  </style>
  