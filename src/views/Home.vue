<template>
  <div class="home">
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <!-- <img src="../assets/rake.png" class="icon"> -->
          <div class="navbar-brand"></div>
          <img src="../assets/shovel.png" class="icon">
        
        
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto offset-sm-9">
              
              <li class="nav-item active">
                <a class="nav-link active" href="#contact"><h4>Contact</h4></a>
              </li>
              <li class="nav-item offset-sm-4">
                <a class="nav-link active" href="#about"><h4>About</h4></a>
              </li>
            </ul>
          </div>
        </nav>
        <div class="parallax">
            <img src="../assets/shovel.png" class="head-img">
          <h1 class="heading">Raking and Shoveling by Cobus</h1>
           <img src="../assets/rake.png" class="head-img">
        </div>
        <div id="about" class="snow"><HelloWorld/></div>
   
   <div id="contact" class="grass"><EmailForm/></div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import EmailForm from '@/components/EmailForm.vue'

export default {
  name: 'home',
  components: {
    HelloWorld,
    EmailForm
  }
}
</script>
<style scoped>
.home {
  font-family: 'Gentium Book Basic', serif;
}
.icon {
  height:40px;
  width:40px;
  margin-right:10px;
 
}
.head-img {
  height:70px;
  margin-right:15px;
  margin-left:15px;
}
.navbar {
  padding-top: 30px;
}
.parallax {
  display:flex;
  justify-content:center;
  align-items:center;
 
    /* The image used */
    background-image: url("../assets/leaves2.jpeg");
    /* filter: blur(8px);
  -webkit-filter: blur(4px); */

    /* Set a specific height */
    min-height: 500px; 
    /* width:fit-content; */

    /* Create the parallax scrolling effect */
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  
}
.heading {
  font-family: 'Milonga', cursive;
  font-size:80px;
  text-shadow: 2px 2px #f8f4f4;
}
.snow {
    border-top:80px solid black;
    border-bottom: 100px solid black;
    background-image: url("../assets/snow.jpeg");
    min-height: 800px;
    width:100%;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
.grass {
  background-image: url("../assets/grass.jpeg");
  min-height:600px;
  width:100%;
}

</style>
