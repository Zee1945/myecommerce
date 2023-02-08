<template>
  <!-- Women Banner Section Begin -->

  <section class="women-banner spad">
      <div class="container-fluid">
          <div class="row">
              <div class="col-lg-12 mt-5">
                  <div class="product-slider">
                      <carousel :items-to-show="3">
                        <slide v-for="slide in 5" :key="1">
                            <div class="product-item">
                          <div class="pi-pic">
                                <img src="../../../public/img/mickey1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="product.html">+ Quick View</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Coat</div>
                                <a href="#">
                                    <h5>Mickey Baggy</h5>
                                </a>
                                <div class="product-price">
                                    $14.00
                                    <span>$35.00</span>
                                </div>
                            </div>
                        </div>
                        </slide>
                        <template #addons>
                              <navigation />
                              <pagination />
                        </template>
                    </carousel> 
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Women Banner Section End -->
</template>

<script setup>
import "vue3-carousel"
import { Carousel, Slide, Pagination, Navigation } from "vue3-carousel";




</script>

<style>

</style>