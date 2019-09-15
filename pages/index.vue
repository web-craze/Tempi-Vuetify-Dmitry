<template>
  <v-layout
    class="mainContent"
    justify-center
    align-center
  >
    <!-- <v-flex
      xs12
      sm8
      md6
    >
leftP
    </v-flex> -->
    <v-row class="scroll-y">


        <v-row
                v-if="!$vuetify.breakpoint.xs"
                justify="center"
                class="mb-5"
        >
            <v-col lg="9" class="py-0">
               <v-row>
                   <v-col lg="6">
                       <div style="float: left">
                       <p v-if="!$vuetify.breakpoint.xs" class="text-center font-weight-bold leftP">Deine Webseite für Jobs</p>
                        <leftSlide />
                       </div>
                   </v-col>

                   <v-col lg="6">
                       <RightForm  style="float:right;"/>
                   </v-col>
               </v-row>
            </v-col>

        </v-row>

      <v-col cols="12" md="6" v-if="$vuetify.breakpoint.xs">
          <p class="text-center font-weight-bold leftP">Deine Webseite für Jobs</p>
          <RightForm />
      </v-col>
      <v-col cols="12" md="5" offset-md="1"  v-if="$vuetify.breakpoint.xs">
          <p v-if="!$vuetify.breakpoint.xs" class="text-center font-weight-bold leftP">Deine Webseite für Jobs</p>
          <leftSlide />
      </v-col>
<!--      <v-col cols="12" md="6" v-if="!$vuetify.breakpoint.xs">-->
<!--          <RightForm />-->
<!--      </v-col>-->


      <v-col cols="12" md="12" >
        <BottomCard />
      </v-col>
      <v-col cols="12" md="12" class="footer" >
        <Footer />
      </v-col>
       
    </v-row>



  </v-layout>
  
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'
import LeftSlide from '~/components/LeftSlide.vue'
import RightForm from '~/components/RightForm.vue'
import BottomCard from '~/components/BottomCard.vue'
import Footer from '~/components/Footer.vue'


export default {
  components: {
    Logo,
    VuetifyLogo,
    LeftSlide,
    RightForm,
    BottomCard,
    Footer
  }, 
   data () {
     return {
       colors: [
         'primary',
         'secondary',
         'yellow darken-2',
         'red',
         'orange',
       ],
     }
   },                                                                                                                                             
}
</script>
<style >
  .mainContent{
    padding: 0px;
  }
  .leftP{
    font-size:45px
  }
  .footer{
    padding:0;
    max-width: 100%;
  }

  @media (max-width:678px) {
   .leftP{
      font-size:40px
    }
  }
</style>

