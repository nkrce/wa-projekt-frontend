<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <p style="color:white">
      Post your book reviews, buy <br>
      and sell second-hand books <br>
      all in one place! 
    </p>

 <div class="container-fluid my-container" style="">
  <div class="btn-group-vertical" role="group" aria-label="Mixed styles example">
    <div class="span2">
     <router-link to="/login"><button type="submit" class="btn btn-dark btn-block">Log in</button></router-link> 
     <router-link to="/signup"><button type="submit" class="btn btn-outline-light btn-block">Sign up</button></router-link>
    </div>
  </div>
 </div>
</div>
</template>

<script>
export default {
  name: 'StartPage',
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
  color: #885AEB;
}
</style>
