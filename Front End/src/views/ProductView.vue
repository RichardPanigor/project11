<template>
    <div class="product">
      <HeaderHB />
        <!-- Breadcrumb Section Begin -->
        <div class="breacrumb-section">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-left">
                    <div class="breadcrumb-text product-more">
                        <router-link to="/">
                            <i class="fa fa-home"></i> Home
                        </router-link>
                        <span>Detail</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Breadcrumb Section Begin -->

    <!-- Product Shop Section Begin -->
    <section class="product-shop spad page-details">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="row">
                        <div class="col-lg-6">
                            <div class="product-pic-zoom">
                                <img class="product-big-img" :src="gambar_default" alt="" />
                            </div>
                            <div class="product-thumbs">
                                <carousel :dots="false" :nav="false" class="product-thumbs-track ps-slider">
                                    <!-- <div class="pt" @click="changeImage(thumbs[0])" :class="thumbs[0] == gambar_default ? 'active' : ''">
                                        <img src="img/products/phimsi-1.png" alt="" />
                                    </div>

                                    <div class="pt" @click="changeImage(thumbs[1])" :class="thumbs[1] == gambar_default ? 'active' : ''">
                                        <img src="img/products/phimsi-2.png" alt="" />
                                    </div>

                                    <div class="pt" @click="changeImage(thumbs[2])" :class="thumbs[2] == gambar_default ? 'active' : ''">
                                        <img src="img/products/phimsi-3.png" alt="" />
                                    </div>

                                    <div class="pt" @click="changeImage(thumbs[3])" :class="thumbs[3] == gambar_default ? 'active' : ''">
                                        <img src="img/products/phimsi-4.png" alt="" />
                                    </div> -->
                                </carousel>
                            </div>
                        </div>
                        <div class="col-lg-6">
                            <div class="product-details text-left">
                                <div class="pd-title">
                                    <span>Bag</span>
                                    <h3>Totebag HIMSI</h3>
                                </div>
                                <div class="pd-desc">
                                    <p>
                                        Totebag ini memiliki resleting dan ukuran 30x40cm, serta memiliki desain hanya pada satu sisi saja. Totebag ini hanya tersedia dalam warna putih. Gausah bingung lagi buat cari tas yang cocok buat kuliah offline, Merchandise Totebag HIMSI solusi nya. Mari miliki totebag favoritmu sekarang! 🤩
                                    </p>
                                    <h4>Rp 30.000</h4>
                                </div>
                                <div class="quantity">
                                    <router-link to="/cart">
                                    <a href="#" class="primary-btn pd-cart">Add To Cart</a>
                                    </router-link>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Product Shop Section End -->
    <RelatedHB />
    <FooterHB />
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  // import HelloWorld from '@/components/HelloWorld.vue'
  import HeaderHB from '@/components/HeaderHB.vue'
  import RelatedHB from '@/components/RelatedHB.vue'
  import FooterHB from '@/components/FooterHB.vue'

  import carousel from "vue-owl-carousel";

  
  
  export default {
    name: 'ProductView',
    components: {
      // HelloWorld
      HeaderHB,
      RelatedHB,
      FooterHB,
      carousel
    },

  data() {
    return {
      gambar_default: "img/products/phimsi-1.png",
      thumbs: [
      "img/products/phimsi-1.png",
      "img/products/phimsi-2.png",
      "img/products/phimsi-3.png",
      "img/products/phimsi-4.png"
      
      ]
    }
  },
  methods: {
    changeImage(urlImage) {
      this.gambar_default = urlImage
    }
  }
  };
  </script>
  
  <style scoped>
.product-thumbs .pt {
  margin-right: 14px;
}
</style>
