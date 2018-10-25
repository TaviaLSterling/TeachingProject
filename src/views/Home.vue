<template>
  <div class="home">
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <img src="../assets/rake.png" class="icon">
          <div class="navbar-brand">Raking and Shoveling by Cobus</div>
          <img src="../assets/shovel.png" class="icon">
        
        
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto offset-sm-9">
              
              <li class="nav-item active">
                <a class="nav-link active" href="#contact">Contact</a>
              </li>
              <li class="nav-item offset-sm-4">
                <a class="nav-link active" href="#about">About</a>
              </li>
            </ul>
          </div>
        </nav>
        <div class="parallax"></div>
        <div id="about" class="snow"><HelloWorld/></div>
   
   <div id="contact" class="grass"></div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
<style scoped>

.icon {
  height:40px;
  width:40px;
  margin-right:10px;
 
}
.navbar {
  margin-top: 50px;
}
.parallax {
    /* The image used */
    background-image: url("../assets/leaves.jpeg");

    /* Set a specific height */
    min-height: 600px; 

    /* Create the parallax scrolling effect */
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
.snow {
    border-top:80px solid black;
    border-bottom: 100px solid black;
    background-image: url("../assets/snow.jpeg");
    min-height: 800px;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
.grass {
  background-image: url("../assets/grass.jpeg");
  min-height:600px;
}
</style>
