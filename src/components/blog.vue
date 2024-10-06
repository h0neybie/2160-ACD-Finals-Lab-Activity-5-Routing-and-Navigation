<template>
     <div class="blog" style="margin-top: 30px">
    
        <h1>{{ title }}</h1>
    <p>Welcome! This is an integration of Vue JS. This will be the blog page<br>where we will display all the blog posts of this website.</p>
    <br>
    <hr>
    
    <main class="container">
  <div class="p-4 p-md-5 mb-4 rounded text-body-emphasis bg-light">
   
  <div class="row mb-2" style="font-family: 'Playfair Display'; display:flex  !important; justify-content:center !important; width:100%  !important; " >
    <div class="col-md-12">
      <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
        <div class="col p-4 d-flex flex-column position-static">
          <br> <br> <br> <br> 
          <h3 class="mb-0">Miss Dior Blooming Bouquet</h3>
           <br>
          <div class="mb-1 text-body-secondary">Oct 1</div>
          <p class="card-text mb-auto">So here's my thoughts about the Miss D Bloomig Bouquet. I've been into fresh spring scents lately and I'm saying this as a College student who goes to school everyday. For me the Blooming Bouquet has the perfect scent for anyone who's looking for the fresh young feminine scent. <br><br>It’s a fresh, fizzy, sweet fragrance that has an underlying hint of florals – it’s very unique for the more popular fragrance collection market. Very spring-esque, it’s how I’d imagine a princess to smell – to be honest, that’s the best way for me to describe it. Super pretty, and very clean too; but not the kind of clean scent that’s too clinical and powdery – it’s not that at all, it’s a sweet-sugary scent that isn’t in your face or sickly, due to that fresh, clean note.
          <br> <br>
          I am highly higly recommending it for those girlies out there who aims for a simple yet elegant fresh scent.
          <br> <br>
          </p>
        <h6 style="text-align: center">- Abby Dizon</h6>
       

          
        </div>
        <div class="col-auto d-none d-lg-block">
        <img  src="../assets/diorr.jpg" style="height:500px">
        </div>
      </div>
    </div>



  </div>

  </div>

</main>

    </div>
  </template>
  
  <script>
  export default {
    name: 'Blog',
    data (){
        return{
            title:'Blog'
        }
    }
  }
  </script>

  <<style scoped>
  
  </style>