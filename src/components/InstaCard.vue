<template>
  <div class="card">
          <div class="card-header text-left">
           <img src="nekipero.png"> Neki Pero
          </div>
          <div class="card-body">
            <img src="ironman.jpg" alt="" class="card-img-top">
          </div>
          
          <div class="card-footer text-muted text-left">
            <img  src="srce.png" alt="slika">  
        <img  src="kom.jpg" alt="slika">  
      <div>  Ivica i Marica like this
</div>
       <div> Tvrtka, Negdje </div>
        2 days ago</div>
        <div class="card-header text-left">
        <div>
          Add comment...
        </div>
        
      </div>
   </div>
        
</template>

<script>
export default {
  name: 'InstaCard',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
