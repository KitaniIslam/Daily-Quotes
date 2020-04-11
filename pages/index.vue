<template> 
  <div class="root-container">
      <navbar class="navbar" />
      <h1 class="bg-quotes">Quotes</h1>
      <h1 class="bg-daily">Daily</h1>
    <div class="container">
    </div>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
export default {
  components: {
    Navbar
  }
}
</script>

<style scoped>
  .root-container {
    width: 100%;
    height: 100vh;
    position: relative;
    overflow: hidden;
  }

  .navbar {
    position: absolute; 
    z-index: 1;
  }

  .bg-quotes {
    position: absolute; 
    left: 196px;
    top: -120px;
    z-index: 2;
    margin: 0;
    font-size: 25rem;
    font-style: normal;
    font-weight: 500;
    line-height: 600px;
    color: #B89A0F;
    opacity: 0.12;

  }

  .bg-daily{
    position: absolute;
    z-index: 2;
    margin: 0;
    left: 854px;
    top: 230px;
    font-size: 25rem;
    font-style: normal;
    font-weight: 500;
    line-height: 600px;
    opacity: 0.12;
  }
</style>
