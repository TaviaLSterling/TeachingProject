<template>
  <div class="hello">
      <div class="card text-white bg-dark offset-sm-3 col-sm-6">
          <div class="card-body">
   <h3> Hello! My name is Cobus.</h3>
   <img src="../assets/Cobus.jpg" class="portrait">
   <h3>I am 10 years old and love playing football and basketball.
      I am a hard worker and an all A student.
      Please let me know if I can help you take care of your lawn this winter!
   </h3>
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
