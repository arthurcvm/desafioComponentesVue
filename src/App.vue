<template>
  <v-app>
    <sideMenu></sideMenu>

    <topBar></topBar>

    <slide></slide>
  
    <myFooter></myFooter>
    
  </v-app>
</template>

<script>
import Footer from '@/components/template/Footer.vue'
import Slide from '@/components/widgets/Slide.vue'
import TopBar from '@/components/template/TopBar.vue'
import Menu from '@/components/template/Menu.vue'
export default {
  components: {
    myFooter: Footer,
    slide: Slide,
    topBar: TopBar,
    sideMenu: Menu,
  }
}
</script>
