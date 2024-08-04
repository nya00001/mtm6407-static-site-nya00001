<template>
    <v-container>
      <v-row align="center" justify="space-between" class="my-5">
        <v-col cols="12" md="6" class="text-center">
          <img src="~assets/img/screenshot.png" alt="WordPress Theme Screenshot" class="screenshot-image">
        </v-col>
        <v-col cols="12" md="6" class="text-center flex-column align-center">
          <p class="description"><strong>Description:</strong><br>
            The "Arcade Theme Park" WordPress theme is a dynamic website designed to showcase an arcade destination. Developed with PHP, this theme leverages the power of WordPress to manage content dynamically and provide a seamless user experience. It features a captivating hero section, visitor testimonials, and a display of various arcade games (classic, modern, and kids' games). An embedded video section offers a sneak peek of the arcade.
          </p>
          <p class="description"><strong>Technical Details:</strong><br>
            <ul>
              <li><strong>PHP Integration:</strong> Utilizes PHP for dynamic content management and theme customization within WordPress.</li>
              <li><strong>Custom Styling:</strong> Modern dark design with a responsive layout.</li>
              <li><strong>Flexbox Layout:</strong> Flexible and visually appealing content arrangement.</li>
              <li><strong>Interactive Elements:</strong> Hover effects on social media icons.</li>
            </ul>
          </p>
          <v-btn class="php-button" href="https://github.com/nya00001/PHP-wordpress-theme" target="_blank">Check Project</v-btn>
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
  
  .description {
    text-align: left;
    font-size: 1rem;
    line-height: 1.5;
    margin-bottom: 1rem;
  }
  
  .description ul {
    padding-left: 1.5rem;
  }
  
  .php-button {
    color: white;
    border: 1px solid white;
    border-radius: 5px;
    margin-top: 10px;
  }
  
  .php-button:hover {
    background-color: white;
    color: black;
  }
  </style>
  