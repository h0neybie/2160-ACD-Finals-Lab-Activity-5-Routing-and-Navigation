<template>
    <div class="about" style="margin-top: 30px">
   
       <h1>{{ title }}</h1>
   <p> Welcome! This is an the integration of Vue JS. This will be the About page<br>where we will learn more of what this website features.</p>
   <hr>

   <div class="position-relative overflow-hidden text-center bg-light">
      <div class="col-md-12 mx-auto my-5">
        <h1 class="display-4 font-weight-normal" style="font-family: fantasy;">Miss Dior</h1>
        <p class="lead font-weight-normal">Blooming Bouquet</p>
        <p class="lead font-weight-normal" style="font-size:16px;">Eau de Toilette - Fresh and Tender Notes</p>
        <img src="../assets/dior.jpg" style="height: 500px; ">
        <hr>
        
        <h3>Description</h3>
        <p>Miss Dior Blooming Bouquet is an instant pleasure, a declaration of love for life that draws you in. <br> Bursting forth in 1947, Miss Dior is Christian Dior's dream come true of an antidote to dreariness. Since then, it has remained untouched, essential to his aim of beauty and happiness. <br> Dior Blooming Bouquet Eau de Toilette has been composed like a floral embrace, both lively and tender. It is a faceted and spontaneous</p>
        <br>
        <hr>

          <h3>Olfactolry Notes</h3>
          <br>
          <p>
           <strong>Bergamot essence<br> </strong>
            Harvested in southern Italy, bergamot essence is obtained by cold expression of fruit peels. It brings a soft, pronounced freshness to the fragrance, and adds a citrus note with special radiance. 
            <br>
            <br>

            <strong>Damascus rose essence and peony note<br> </strong>
            Damascus rose exudes a subtly spicy floral note.
            <br>
            <br>

            <strong>White musks<br> </strong>
            White musks procure a slightly powdery, cottony effect that gives the fragrance the impression of enveloping softness.
            </p>
        <br>
        <hr>

      <h3>Application Tips</h3>
      <p>1. Cleanse your skin with the airy texture of Miss Dior Foaming Shower Gel.</p>
      <p>2. Then invigorate the skin with the light and fresh formula of Miss Dior Silky Body Mist.</p>
      <p>3. Perfume with Miss Dior Blooming Bouquet, then refresh your hair with Miss Dior Hair Mist.</p>
      </div>
    </div>
    <hr>

    

   </div>
 </template>
 
 <script>
 export default {
   name: 'About',
   data (){
       return{
           title:'About'
       }
   }
 }
 </script>

 <<style scoped>


 
 </style>