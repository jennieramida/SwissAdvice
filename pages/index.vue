<template>
  <section class="container">
    <div>
       <img src="~/assets/images/pattern.png" class="pattern">
     
      <img src="~/assets/images/logo.png" class="image-size">
        <img src="~/assets/images/pattern.png" class="pattern2">
     
      <h2 class="subtitle">
     Under Construction   </h2>
    <h2 class="subtitle-white">
       We are currently working on new amazing website. <br> Please stay tuned! </h2>
    
      
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: #5f8eb6;
  position: relative;
}

.pattern {
  position: absolute;
  height: 150px;
  top: 30px;
  left: 0px;
  opacity: 0.7;
  overflow: hidden;
}

.pattern2 {
  position: absolute;
  height: 180px;
  top: 70vh;
  right: 0px;
  overflow: hidden;
}

.image-size {
  height: 400px;
}

.subtitle {
  font-weight: 400;
  font-size: 28px;
  color: #fff;
  word-spacing: 5px;
}

.subtitle-white {
  font-weight: 300;
  font-size: 20px;
  color: #fff;
  word-spacing: 5px;
}

.links {
  padding-top: 15px;
}
</style>

