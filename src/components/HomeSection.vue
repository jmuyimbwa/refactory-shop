<template>
<div class="row">
  <div class="col-sm-4">
     <div class="card" style="width: 18rem;">
        <img :src= "require('/home/jonah/workspace/jack/pro3/refactory-shop/src/assets/pexels-christina-morillo-1181352.jpg')" class="card-img-top" alt="..." />
        <div class="card-body">
        <h5 class="card-title">We're advancing Uganda's tech industry</h5>
        <p class="card-text">Developed in partnership with the tech sector, Refactory is the industry's blueprint for hiring developers.</p>
        <a href="#" class="btn btn-primary">Apply Now</a>
        </div>
    </div>
  </div>
  <div class="col-sm-8">
    <div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" :src="require('/home/jonah/workspace/jack/pro3/refactory-shop/src/assets/pexels-christina-morillo-1181352.jpg')" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" :src="require('/home/jonah/workspace/jack/pro3/refactory-shop/src/assets/pexels-markus-spiske-4439901.jpg')" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" :src="require('/home/jonah/workspace/jack/pro3/refactory-shop/src/assets/pexels-thisisengineering-3861964.jpg')" alt="Third slide">
    </div>
  </div>
</div> 
  </div>
</div>
 <div class="row row-cols-1 row-cols-md-4 g-4 mt-auto ">
    <div class="col">
      <div class="card h-100">
        <img :src="require('/home/jonah/workspace/jack/pro3/refactory-shop/src/assets/images.png')" width="50" height="150" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Foundations of Software Decelopment</h5>
          <p class="card-text">An 8-week program designed to introduce foundational software development skills to high school graduates or holiday-makers.</p>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100">
        <img :src="require('/home/jonah/workspace/jack/pro3/refactory-shop/src/assets/catalyst.png')" width="50" height="150" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Step 1: Catalyst Course</h5>
          <p class="card-text">A focused three-month program that includes training in leadership, critical thinking, IT project management, as well as introductions to different technologies.</p>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100">
        <img :src="require('/home/jonah/workspace/jack/pro3/refactory-shop/src/assets/bootcamp4.png')" width="50" height="150"  class="card-img-top" alt="...">
        
        <div class="card-body">
          <h5 class="card-title">Step 2: Bootcamp</h5>
          <p class="card-text">A six-month boot camp, where a key component is practical learning through projects with industry partners.</p>
          
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100">
        <img :src="require('/home/jonah/workspace/jack/pro3/refactory-shop/src/assets/hired.png')" width="50" height="150" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Step 3: Get Hired!</h5>
          <p class="card-text">We help our students enter the tech industry the way they want, either as employees or entrepreneurs.</p>
        </div>
      </div>
    </div>
  </div>
   
  

</template>

<script>
export default {
    name : "HomeSection",
}
</script>

<style scoped>
    .section{
        background-color: purple;
    }


</style>