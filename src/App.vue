<template>
  <AppHeader :navItems="navItems" />
  <AppMain />
  <AppFooter 
  :footerItemsServices="footerItemsServices"
  :footerItemsResources="footerItemsResources"
  :footerItemsCompany="footerItemsCompany"
  />
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
      ],

      footerItemsServices:[
        {title: "Marketing Plan"},
        {title: "Sales Development"},
        {title: "Digital Marketing"},
        {title: "Pricing"},
        {title: "Why Us"},
        {title: "Case Studies"}
      ],

      footerItemsResources:[
        {title: "Learning Center"},
        {title: "Video Tutorials"},
        {title: "Customers"},
        {title: "Blog"}
      ],

      footerItemsCompany:[
        {title: "Who We Are"},
        {title: "Contact Us"},
        {title: "Careers"}
      ]
    }
  }
}
</script>

<style lang="scss">
  @import "./styles/general.scss"
</style>  