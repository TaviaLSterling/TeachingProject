<template>
  <div class="hello container-fluid row">
      <div class="card text-white bg-dark offset-sm-3 col-sm-7">
          <div class="card-body">
   <h3> Hello! My name is Cobus.</h3>
   <img src="../assets/Cobus.jpg" class="portrait">
   <h3>I am 10 years old and love playing football and basketball.
     <br> I am a hard worker and an all A student.<br>I am trying to earn money so that I can buy myself a new scooter.
    <br>I can rake and bag leaves or shovel your sidewalk and driveway.<br>
      Please let me know if I can help you take care of your lawn this fall and winter!
   </h3>
          </div>
        </div>
        <div class="card text-white bg-dark offset-sm-3 col-sm-7">
            <div class="card-body">
              <h5>My goal is to save $100</h5><br>
              <h5>This is my progress so far:</h5>
            <div class="progress" style="height: 30px;">
                <div class="progress-bar" role="progressbar" style="width: 25%" aria-valuenow="0" aria-valuemin="0" aria-valuemax="100">$10</div>
              </div>
            </div>
        </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin-top:30px;
}
.portrait {
height:40vh;
}
.card {
  margin-top:30px;
  margin-bottom:30px;
}
</style>
