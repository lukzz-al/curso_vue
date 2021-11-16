<template>
  <v-app>
    <app-menu/>
    <app-headerBar/>
    <app-carousel/>
    <app-footer/>
  </v-app>
</template>

<script>
import Carousel from '@/components/widgets/Carousel.vue'
import Menu from '@/components/template/Menu.vue'
import HeaderBar from '@/components/template/HeaderBar.vue'
import Footer from '@/components/template/Footer.vue'
export default {
  components:{
    'app-headerBar': HeaderBar,
    'app-carousel': Carousel,
    'app-menu': Menu,
    'app-footer': Footer
  },
  data() {
    return {
      
    }
  }
}
</script>