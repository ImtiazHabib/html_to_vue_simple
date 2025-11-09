<script setup>
import { image_src, image_title } from './data/data';
const title = "welcome to My vue Practice code ";
const width="100px";
</script>

<template>
   <section class="section">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
             <h1>{{ title }}</h1>
          </div>
        </div>
      </div>
   </section>

   <section class="image_card">
     <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="inner_image_card">
            <div class="card" style="width: 18rem;">
              <img :src="image_src" class="card-img-top" alt="..." :width="width">
              <div class="card-body">
                <h5 class="card-title">{{ image_title }}</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card’s content.</p>
                <a href="#" class="btn btn-primary">search it on Pixel</a>
              </div>
            </div>
          </div>
        </div>
      </div>
     </div>
   </section>
</template>

<style scoped>

</style>
