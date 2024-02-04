<template>
<nav class="navbar navbar-light sticky-top" style="background: linear-gradient(to bottom, #563095, #AE77B3);">
  <a class="navbar-brand" href="/homepage">
    <img src="../assets/logo.png" width="30" height="30" alt="">
  </a>
  
  <form class="form-inline">
    <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
    <router-link to="/search"><button class="btn btn-outline-light my-2 my-sm-0" type="submit">Search</button></router-link>  
  </form>

  <a class="navbar-brand ml-auto" href="#">
    <img src="../assets/cart.png" width="30" height="30" alt="">
  </a>

  <a class="navbar-brand ml-2" href="/profile">
    <img src="../assets/user.png" width="30" height="30" alt="">
  </a>
</nav>

<div class="container">
  <div class="row">
    <div class="col" style="background-color: #AE77B3; border-bottom-left-radius: 100px;">
      <br><p><a href="/search" style="color: white">Book Sales</a></p>
    </div>
    <div class="col" style="background-color: #e7e1e8; border-bottom-right-radius: 100px;">
      <br><p> <a href="/search2" style="color: black">Book Reviews</a></p>
    </div>
  </div>
</div>


<div class="container">
  <div class="row">
    <div class="col-sm"> <br>
      <my-item-card/>
    </div>
    <div class="col-sm"> <br>
       <my-item-card/>
    </div>
    <div class="col-sm"> <br>
       <my-item-card/>
    </div>
  </div>
  <div class="row">
    <div class="col-sm"> <br>
      <my-item-card/>
    </div>
    <div class="col-sm"> <br>
       <my-item-card/>
    </div>
    <div class="col-sm"> <br>
       <my-item-card/>
    </div>
  </div>
</div>
<div class="container" style=" height: 15vh">
  <br>
</div>
</template>

<script>
// @ is an alias to /src
import ItemCard from '@/components/ItemCard.vue'

export default {
  name: 'ItemCard',
  components: {
    'my-item-card': ItemCard,
  }
}
</script>

<style scoped>
.about {
  background:#885AEB;
  width: 100%;
  height: 12vh;
  border-bottom-left-radius: 100px; 
  border-bottom-right-radius: 100px; 
}
.col-sm {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>

