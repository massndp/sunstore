<template>
  <div class="home">
  <HeaderSunshop/>
  <HeroSunshop/>
  <Woman/>
  <Instagram/>
  <Partners/>
  <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSunshop from '@/components/HeaderSunshop.vue';
import HeroSunshop from '@/components/HeroSunshop.vue';
import Woman from '@/components/Woman.vue';
import Instagram from '@/components/Instagram.vue';
import Partners from '@/components/Partners.vue';
import Footer from '@/components/Footer.vue';




export default {
  name: 'Home',
  components: {
    HeaderSunshop,
    HeroSunshop,
    Woman,
    Instagram,
    Partners,
    Footer
}
}
</script>
