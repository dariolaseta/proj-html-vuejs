<template>
  <AppHeader :navItems="navItems" />
  <AppMain />
  <AppFooter />
</template>

<script>
import AppHeader from "./components/AppHeader.vue"
import AppMain from "./components/AppMain.vue"
import AppFooter from "./components/AppFooter.vue"

export default {
  name: "App",
  components:{
    AppHeader,
    AppMain,
    AppFooter
  },
  data(){
    return{
      navItems:[
        {title: "Home"},
        {title: "Services"},
        {title: "Why Us"},
        {title: "Case Studies"},
        {title: "About"},
        {title: "Blog"},
      ]
    }
  }
}
</script>

<style lang="scss">
  @import "./styles/general.scss"
</style>  