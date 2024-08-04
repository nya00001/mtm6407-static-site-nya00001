<template>
    <v-container>
      <div id="component-portfolio" class="d-flex flex-column justify-center align-center text-center">
        <img src="~assets/img/photo-me.jpeg" alt="me">
        <h1>{{ name }}</h1>
        <p>{{ description }}</p>
        <div class="d-flex justify-center">
          <a href="https://github.com/nya00001" target="_blank" title="Github"><i class="fab fa-github mx-2"></i></a>
          <a href="https://www.linkedin.com/in/mohamed-nya-742953261/" target="_blank" title="LinkedIn"><i class="fab fa-linkedin mx-2"></i></a>
          <a href="mailto:mnya99@gmail.com" target="_blank" title="Email"><i class="fas fa-envelope mx-2"></i></a>
        </div>
      </div>
    </v-container>
  </template>
  
  <script>
  export default {
    data() {
      return {
        name: 'Mohamed Nya',
        description: 'Hello, I am Mohamed Nya. I am a Frontend Web Developer. Welcome to my projects website! This site showcases my projects and skills in web development, highlighting my proficiency in various frontend technologies. Here, you will find detailed information about my projects, including the tools and frameworks used. From t-shirt storefronts to contact book applications, each project reflects my dedication to creating responsive, dynamic, and user-friendly web applications. Explore my work, and feel free to reach out if you have any questions or collaboration ideas!'
      }
    }
  }
  </script>
  
  <style scoped lang="scss">
  #component-portfolio {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
  
    img {
      width: 20vw;
      border-radius: 10%;
    }
  
    i {
      font-size: 3rem;
      padding: 1rem;
      color: white;
    }
  
    i:hover {
      color: teal;
    }
  }
  </style>
  