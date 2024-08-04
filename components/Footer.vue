<template>
    <v-footer class="footer">
      <v-container>
        <div class="footer-content text-center">
          <p>&copy; 2024 Mohamed Nya. All rights reserved.</p>
          <div class="d-flex justify-center">
            <a href="https://github.com/nya00001" target="_blank" title="Github"><i class="fab fa-github mx-2"></i></a>
            <a href="https://www.linkedin.com/in/mohamed-nya-742953261/" target="_blank" title="LinkedIn"><i class="fab fa-linkedin mx-2"></i></a>
            <a href="mailto:mnya99@gmail.com" target="_blank" title="Email"><i class="fas fa-envelope mx-2"></i></a>
          </div>
        </div>
      </v-container>
    </v-footer>
  </template>
  
  <script>
  export default {
  }
  </script>
  
  <style scoped>
  .footer {
    background-color: #000;
    color: #fff;
    padding: 1rem 0;
  }
  
  .footer-content {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  
  i {
    font-size: 2rem;
    padding: 0.5rem;
    color: white;
  }
  
  i:hover {
    color: teal;
  }
  </style>
  