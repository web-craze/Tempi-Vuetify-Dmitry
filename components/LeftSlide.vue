<template>
    <v-card
            elevation="24"
            max-width="614"
            class="mx-auto"
            color="transparent"
    >
        <v-carousel :show-arrows="false" :height="482">
            <v-carousel-item
                    v-for="(color, i) in colors"
                    :key="color"
            >
                <v-sheet
                        :color="color"
                        height="100%"
                        tile
                        class="leftSlide"
                >
                    <v-row
                            class="fill-height1"
                            align="center"
                            justify="center"
                    >

                        <div style="position:relative; margin-left:50px">
                            <v-img :src="require('@/assets/DESKTOP/NoPath - Kopie.png')"
                                   style="margin-right:-50px"></v-img>
                            <v-img :src="require('@/assets/DESKTOP/NoPath - Kopie (2).png')"
                                   style="z-index:1; margin-top: -40px; margin-left: -50px;"></v-img>
                        </div>
                        <div style="color:#546E7A" align="center" justify="center">
                            <span class="font-italic font-weight-bold" style="color: #546E7A">Markus H</span>
                            <p class="text-xs-center" style="font-size: 16px;">Markus H. Brandschutz Consulting</p>
                            <p class="text-xs-center">Tempi ermöglicht uns eine schnelle und einfache Abwicklung auf der
                                Suche nach neuen Mitarbeiter..</p>
                        </div>
                    </v-row>
                </v-sheet>
            </v-carousel-item>
        </v-carousel>
    </v-card>
</template>

<script>

    export default {
        data() {
            return {
                colors: [
                    '#FFFFFF',
                    '#FFFFFF',
                    '#FFFFFF'
                ],
            }
        },
    }
</script>
<style>
    .v-row {
        font-size: 16px;
    }

    .fill-height1 {
        padding: 33px;
    }

    .leftSlide {
        display: flex;
        align-items: center;
    }

    .transparent {
        background-color: white !important;
        opacity: 0.65;
        border-color: transparent !important;
    }
</style>
