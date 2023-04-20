<template>
  <!-- Women Banner Section Begin -->
  <section class="women-banner spad">
      <div class="container-fluid">
          <div class="row">
              <div class="col-lg-12 mt-5">
                <div class="section-title">
                    <h2>Wadah Usaha HIMSI</h2>
                </div>
                  <carousel class="product-slider" :items="3" :dots="false" :autoplay="true" :nav="false" :loop="true">
                      <div class="product-item">
                          <div class="pi-pic">
                              <img src="img/iklan/iklan-1.png" alt="" />
                               <ul>
                                  <li class="quick-view"><a href="https://www.instagram.com/ruangjenuh_coffee"> Explore Now</a></li>
                              </ul>
                          </div>
                          <div class="pi-text">
                              <a href="https://www.instagram.com/ruangjenuh_coffee">
                                  <h5>Lukisan</h5>
                              </a>
                              <div class="product-price">
                                @namfy.art22
                              </div>
                          </div>
                      </div>
                      <div class="product-item">
                          <div class="pi-pic">
                              <img src="img/iklan/iklan-2.png" alt="" />
                              <ul>
                                  <li class="quick-view"><a href="https://www.instagram.com/ruangjenuh_coffee"> Explore Now</a></li>
                              </ul>
                          </div>
                          <div class="pi-text">
                              <a href="#">
                                  <h5>Rizan Food</h5>
                              </a>
                              <div class="product-price">
                                @rizan.food
                              </div>
                          </div>
                      </div>
                      <div class="product-item">
                          <div class="pi-pic">
                              <img src="img/iklan/iklan-3.png" alt="" />
                              <ul>
                                  <li class="quick-view"><a href="https://www.instagram.com/ruangjenuh_coffee"> Explore Now</a></li>
                              </ul>
                          </div>
                          <div class="pi-text">
                              <a href="#">
                                  <h5>Coffee Shop</h5>
                              </a>
                              <div class="product-price">
                                @ruangjenuh_coffee
                              </div>
                          </div>
                      </div>
                      <div class="product-item">
                          <div class="pi-pic">
                              <img src="img/iklan/iklan-4.png" alt="" />
                              <ul>
                                  <li class="quick-view"><a href="https://www.instagram.com/ruangjenuh_coffee"> Explore Now</a></li>
                              </ul>
                          </div>
                          <div class="pi-text">
                              <a href="#">
                                  <h5>Beauty Glow</h5>
                              </a>
                              <div class="product-price">
                                @glowinsidee
                              </div>
                          </div>
                      </div>
                      <div class="product-item">
                          <div class="pi-pic">
                              <img src="img/iklan/iklan-5.png" alt="" />
                              <ul>
                                  <li class="quick-view"><a href="https://www.instagram.com/ruangjenuh_coffee"> Explore Now</a></li>
                              </ul>
                          </div>
                          <div class="pi-text">
                              <a href="#">
                                  <h5>Bucket & Box Gift</h5>
                              </a>
                              <div class="product-price">
                                @aeter.gift
                              </div>
                          </div>
                      </div>
                      <div class="product-item">
                          <div class="pi-pic">
                              <img src="img/iklan/iklan-6.png" alt="" />
                              <ul>
                                  <li class="quick-view"><a href="https://www.instagram.com/ruangjenuh_coffee"> Explore Now</a></li>
                              </ul>
                          </div>
                          <div class="pi-text">
                              <a href="#">
                                  <h5>Bucket</h5>
                              </a>
                              <div class="product-price">
                                @alebucket.id
                              </div>
                          </div>
                      </div>
                      <div class="product-item">
                          <div class="pi-pic">
                              <img src="img/iklan/iklan-7.png" alt="" />
                              <ul>
                                  <li class="quick-view"><a href="https://www.instagram.com/ruangjenuh_coffee"> Explore Now</a></li>
                              </ul>
                          </div>
                          <div class="pi-text">
                              <a href="#">
                                  <h5>Florubish Florist</h5>
                              </a>
                              <div class="product-price">
                                @florubish
                              </div>
                          </div>
                      </div>
                  </carousel>
              </div>
          </div>
      </div>
  </section>
  <!-- Women Banner Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "IklanHB",
  components: {
      carousel
  }
}
</script>

<style scoped>
.product-item {
margin-right: 25px;
}
.pi-pic img {
height: 450px;
}
</style>