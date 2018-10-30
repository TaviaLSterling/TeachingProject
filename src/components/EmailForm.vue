<template>
        <div class="form row">
          <div class="card text-white bg-dark offset-sm-3 col-sm-6">
            <div class="card-body">
                <h3>Please email me to schedule!</h3>
         <form action="mailto:TaviaSterling@outlook.com" method="post" enctype="text/plain">
           <h4>Name:</h4>
            <input type="text" name="name">
            <h4>Email:</h4>
            <input type="text" name="mail"><br>
            <h4>Let me know how I can help you:</h4>
            <input type="text" name="comment" size="50"><br><br>
            <input class="btn btn-primary" type="submit" value="Send">
            </form>
            </div>
            </div>
        </div>
      </template>
      
      <script>
      export default {
        name: 'EmailForm'
      }
      </script>
      
      <!-- Add "scoped" attribute to limit CSS to this component only -->
      <style scoped>
      h3 {
        margin-top:30px;
      }
      .card {
        margin-top:50px;
      }
      </style>
      