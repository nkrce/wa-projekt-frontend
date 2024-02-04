<template>
  <div class="home">
    <h2 style="color:white"> ReadRevend </h2>
    <img alt="Vue logo" src="../assets/logo.png" style="width:200px;height:200px;">
    <HelloWorld/>
  </div>

</template>



<script>
// @ is an alias to /src
import HelloWorld from '@/components/LoginSignup.vue'

export default {
  name: 'LoginSignup',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
.home {
  background: linear-gradient(to bottom, #563095, #AE77B3);
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
