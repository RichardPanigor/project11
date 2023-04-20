<template>
  <div class="home">
    <HeaderHB />
    <HeroHB />
    <WomenHB />
    <IklanHB />
    <PartnerHB />
    <FooterHB />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderHB from '@/components/HeaderHB.vue'
import HeroHB from '@/components/HeroHB.vue'
import WomenHB from '@/components/WomenHB.vue'
import IklanHB from '@/components/IklanHB.vue'
import PartnerHB from '@/components/PartnerHB.vue'
import FooterHB from '@/components/FooterHB.vue'


export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    HeaderHB,
    HeroHB,
    WomenHB,
    IklanHB,
    PartnerHB,
    FooterHB
    
  }
}
</script>
