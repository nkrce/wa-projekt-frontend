<template>

<div class="card">
  <div class="card-header">
    @username
  </div>
  <div class="card-body">
    <img class="card-img-top" src="../assets/book.png" alt="Card image cap">
    <h5 class="card-title">Name of the book</h5>
    <p class="card-text">Describe the sale in more detail if needed.</p>
    <p class="price">€19.99</p>
    <a href="#" class="btn btn-light" style="background-color: #AE77B3" >Add to cart</a>
  </div>
</div>

</template>

<script>
export default {
  name: 'ItemCard',
  props: {
    msg: String
  }
}
</script>

