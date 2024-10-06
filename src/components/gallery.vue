<template>
<div class="blog" style="margin-top: 30px">
    <h1>{{ title }}</h1>
<p>Welcome! This is an integration of Vue JS. This will be the Gallery page<br>where we will display all the featured media of this website.</p>
<br>
<hr>
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
  export default {
    name: 'Gallery',
    data (){
        return{
            title:'Gallery'
        }
    }
  }
  </script>

  <<style scoped>
  
  </style>