<template class="wholeContent">
  <!-- <v-parallax
    dark
    :src="require('@/assets/DESKTOP/60.png')"
    height="100%"
    jumbotron
    class="nonPadding"
  > -->
<div class="back">
  <v-app style="background: none" class="nonPadding">

    <v-app-bar
      :clipped-left="clipped"
      absolute
      scroll-off-screen
      app
      color="primary"
      class="nonPadding"
      style="background-color:black"
      height="64px"
    >

    <v-col cols=4>
      <a href="/" title="Return To Home">
        <img height="50" alt="" class="logo mt-3" srcset="@/assets/DESKTOP/tempi-logo-white.png" />
      </a>
    </v-col>
    <v-col cols=8>
      <v-toolbar-title class="login_title">
        LOGIN
      </v-toolbar-title>
    </v-col>
    </v-app-bar>
    
    <v-content>
      <v-container class="WholeContainer">
        <nuxt />
      </v-container>
    </v-content>

    <v-footer
      :fixed="fixed"
      app
      class="footer"
    >
      <span>Made with <i data-v-b3e68e08="" aria-hidden="true" class="v-icon notranslate mdi mdi-cards-heart theme--dark" style="font-size: 14px;"></i> &
      <i data-v-b3e68e08="" aria-hidden="true" class="v-icon notranslate mdi mdi-coffee theme--dark" style="font-size: 16px;"></i></span>
    </v-footer>
  </v-app>
  <!-- </v-parallax> -->
</div>
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
<style>
   .v-app-bar {
    background-color: #37474F;
  }
  .nonPadding{
    padding: 0px;
  }
  .v-toolbar__content{
    background-color: #37474F
  }
  .logo{
    padding-left: 20px
  }
  .login_title{
    text-align: right;
    font-size: 14px;
  }
  .theme--dark.v-footer{
    background-color: #37474F
  }
  .v-parallax__image {
    width: 100% !important;
  }
  .parallax-window {
    min-height: 400px;
    background: transparent;
  }
.back{
    background-image: url(../assets/DESKTOP/60.png);
    background-attachment: fixed;
    background-position: 50%;
    background-repeat: no-repeat;
    background-size: cover;
}
.WholeContainer{
  padding:0
}

</style>
