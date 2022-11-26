<script setup>
import Body1 from "./components/Body.vue"
import Footer1 from "./components/Footer.vue"
import Header1 from "./components/Header.vue"
</script>

<template>
  <div class="main">
    <Header1/>
    <div class="under">
      <Body1/>
      <Footer1/>
    </div>
  </div>

</template>

<style scoped>
  .main{
    width: 100%;
    height: 100%;
  }
  .under{
    width: 100%;
    display: flex;
    flex-direction: column;
    margin-top: 15%;
  }
</style>
