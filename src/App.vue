<template>
  <div id="app" class="app">
    <desktop-nav id="desktop-nav"/>
    <mobile-nav id="mobile-nav"/>
    <div class="view-container">
      <router-view/>
    </div>
<!--.nav
     padding: 30px
     a
       font-weight: bold
       color: #2c3e50

  .view-container
    color: #2c3e50-->
  </div>
</template>

<script>
  import DesktopNav from "./components/DesktopNav"
  import MobileNav from "./components/MobileNav";

  export default {
    data() {
      return {

      }
    },
    components: {
      DesktopNav,
      MobileNav
    }
  }
</script>

<style lang="sass" scoped>
  .app
    font-family: 'Avenir', Helvetica, Arial, sans-serif
    -webkit-font-smoothing: antialiased
    -moz-osx-font-smoothing: grayscale

  .view-container
    width: 79vw
    padding: 1.5em
    margin-left: 20vw
    box-sizing: border-box
    min-height: 100vh

  #mobile-nav
    display: none

  @media screen and (max-width: 1096px)
    .view-container
      width: 100%
      margin-left: 0
    #desktop-nav
      display: none
    #mobile-nav
      display: flex

</style>