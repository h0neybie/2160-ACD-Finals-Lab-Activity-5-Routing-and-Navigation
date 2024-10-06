<template>
  <div class="home" style="margin-top: 30px">
    
    <h1>Home</h1>
    <p> Welcome! This is an integration of Vue JS. This will be the home page<br>where we will display all the features of this website.</p>
  <br>
  <hr>  
       <div class="position-relative overflow-hidden text-center bg-light">
        <h1 class="display-4 font-weight-normal" style="font-family: fantasy;">Miss Dior</h1>
        <p class="lead font-weight-normal">Blooming Bouquet</p>
        <p class="lead font-weight-normal" style="font-size:16px;">Eau de Toilette - Fresh and Tender Notes</p>
        <img src="../assets/dior.jpg" style="height: 500px;">
        <hr>
     </div>
  <!-- Gallery -->
<div class="row">
  <div class="col-lg-4 col-md-12 mb-4 mb-lg-0">
    <img
      src="../assets/1.jpg"
      class="w-100 shadow-1-strong rounded mb-4"
      alt="Boat on Calm Water"
    />

    <img
      src="../assets/2.jpg"
      class="w-100 shadow-1-strong rounded mb-4"
      alt="Wintry Mountain Landscape"
    />
  </div>

  <div class="col-lg-4 mb-4 mb-lg-0">
    <img
       src="../assets/3.jpg"
      class="w-100 shadow-1-strong rounded mb-4"
      alt="Mountains in the Clouds"
    />

    <img
      src="../assets/5.jpg"
      class="w-100 shadow-1-strong rounded mb-4"
      alt="Boat on Calm Water"
    />
  </div>

  <div class="col-lg-4 mb-4 mb-lg-0">
    <img
       src="../assets/6.jpg"
      class="w-100 shadow-1-strong rounded mb-4"
      alt="Waves at Sea"
    />

    <img
      src="../assets/4.jpg"
      class="w-100 shadow-1-strong rounded mb-4"
      alt="Yosemite National Park"
    />
  </div>
</div>
<!-- Gallery -->
  <hr>
 </div>
 
</template>
 <script>
  export default{
    name: "home",
    data () {
      return {
        msg: "Welcome to Your Vue.js App"
      } 
    }
  }
 </script>

 <<style scoped>

 </style>