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
        <div class="parallax"></div>
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
.navbar {
  padding-top: 30px;
}
.parallax {
    /* The image used */
    background-image: url("../assets/leaves.jpeg");
    filter: blur(8px);
  -webkit-filter: blur(4px);

    /* Set a specific height */
    min-height: 500px; 
    /* width:fit-content; */

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
