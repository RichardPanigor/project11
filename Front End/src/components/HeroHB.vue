<template>
    <!-- Hero Section Begin -->
    <section class="hero-section">
      <carousel class="hero-items" :items="1" :nav="false" :autoplay="true" :loop="true">

        <div class="single-hero-items set-bg" style="background-image: url('/img/herohb-1.png')">
          <div class="container text-left">
            <div class="row">
              <div class="col-lg-5">
                <span>JAHIM</span>
                <h1>Jaket Himpunan</h1>
                <p>Jaket HIMSI merupakan suatu identitas dari HIMSI UIN Jakarta yang menandakan ciri khas himpunan, sebagai bentuk perjuangan para pendiri himpunan. Beli JAHIM sekarang juga untuk outfit harian kamu!</p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
        <div class="single-hero-items set-bg" style="background-image: url('/img/herohb-2.png')">
          <div class="container text-left">
            <div class="row">
              <div class="col-lg-5">
                <span>T-SHIRT</span>
                <h1>T-Shirt HIMSI</h1>
                <p>T-Shirt merupakan suatu identitas dari HIMSI UIN Jakarta yang menandakan ciri khas himpunan, sebagai bentuk perjuangan para pendiri himpunan. Beli JAHIM sekarang juga untuk outfit harian kamu!</p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
        <div class="single-hero-items set-bg" style="background-image: url('/img/herohb-3.png')">
          <div class="container text-left">
            <div class="row">
              <div class="col-lg-5">
                <span>PDH</span>
                <h1>Pakaian Dinas Harian</h1>
                <p>PDH merupakan pakaian yang dikenakan oleh anggota pengurus HIMSI pada saat melaksanakan kegiatan yang diikutinya. Kamu pengurus tapi belum punya PDH? Buruan checkout sekarang juga!</p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>

      </carousel>
    </section>
    <!-- Hero Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
    name: "HeroShayna",
    components: {
        carousel
    }
}
</script>