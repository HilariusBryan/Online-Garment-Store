<template>
  <div class="home">
   <HeaderGarment />
   <HeroGarment />
   <WomenGarment />
   <InstaGarment />
   <PartnerGarment />
   <FooterGarment />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderGarment from '@/components/HeaderGarment.vue';
import HeroGarment from '@/components/HeroGarment.vue';
import WomenGarment from '@/components/WomenGarment.vue';
import InstaGarment from '@/components/InstaGarment.vue';
import PartnerGarment from '@/components/PartnerGarment.vue';
import FooterGarment from '@/components/FooterGarment.vue';


export default {
  name: 'Home',
  components: {
    HeaderGarment,
    HeroGarment,
    WomenGarment,
    InstaGarment,
    PartnerGarment,
    FooterGarment
    
  }
}
</script>
