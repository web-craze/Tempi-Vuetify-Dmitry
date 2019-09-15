<template>

    <nav>

        <v-toolbar flat dark app color="primary" height="80">
            <v-toolbar-side-icon v-if="!drawer" @click="drawer = true" class="hidden-md-and-up"></v-toolbar-side-icon>

            <v-icon v-else @click="drawer = false">close</v-icon>

            <v-toolbar-title class="mt-1">
                <a href="/" title="Return To Home">
                    <!-- <img height="100" alt="" class="logo" style="" srcset="@/assets/DESKTOP/60.png 992w," /> -->
                    <!-- <img height="150" alt="" class="logo hidden-sm-and-up" onerror="this.src='@/assets/images/color-logo-land.png',this.onerror=null" src="@/assets/images/color-logo-land.svg" /> -->
                </a>

            </v-toolbar-title>

            <v-spacer></v-spacer>


        </v-toolbar>


    </nav>

</template>

<script>

    // import Login from '@/components/Login'
    // import Compose from '@/components/Compose'
    // import Register from '@/components/Register'


    export default {
        components: {},
        data() {
            return {
                drawer: false
            }

        }
    }
</script>

<style>


    @media only screen and (max-width: 960px) {
        /* .logo {
         position: absolute; top: -15px; left: 50%; transform: translate(-50%, 0%);
        } */
    }

</style>