<template>
    <div>
        <v-row
                justify="center"
                class="mb-5"
                v-if="!$vuetify.breakpoint.xs"
        >
            <v-col lg="9" class="py-0">
                <v-layout row wrap>
                    <v-flex xs12>
                        <v-card
                                class="white"
                        >
                            <v-img
                                    class="white--text"
                                    height="200px"
                                    :src="require('@/assets/DESKTOP/NoPath - Kopie mcd.png')"
                            >
                                <v-card-title class="align-end fill-height">Crewmitarbeiter/IN</v-card-title>
                            </v-img>


                            <v-list-item three-line>
                                <v-list-item-avatar
                                        size="80"
                                        tile
                                >
                                    <v-img :src="require('@/assets/DESKTOP/NoPath-1.png')"></v-img>
                                </v-list-item-avatar>
                                <v-list-item-content class="align-self-start mt-3">
                                    <v-list-item-title
                                            class="headline mb-2"
                                            style="color:#546E7A"
                                    >McDonald's
                                    </v-list-item-title>
                                    <v-list-item-subtitle style="color:#546E7A">8105 Regensdorf</v-list-item-subtitle>
                                </v-list-item-content>
                            </v-list-item>
                            <div align="center" justify="center" class="text-uppercase font-weight-bold pb-2"><a
                                    style="color:#2196F3">anschauen & bewerben</a></div>
                        </v-card>
                    </v-flex>
                    <v-flex class="mt-3" xs12>
                        <v-card
                                class="white"
                        >
                            <v-img
                                    class="white--text"
                                    height="200px"
                                    :src="require('@/assets/DESKTOP/NoPath - Kopie senior.png')"
                            >
                                <v-card-title class="align-end fill-height">Senior Accountant</v-card-title>
                            </v-img>


                            <v-list-item three-line>
                                <v-list-item-avatar
                                        size="80"
                                        tile
                                >
                                    <v-img :src="require('@/assets/DESKTOP/NoPath - Kopie-1.png')"></v-img>
                                </v-list-item-avatar>
                                <v-list-item-content class="align-self-start mt-3">
                                    <v-list-item-title
                                            class="headline mb-2"
                                            style="color:#546E7A"
                                    >LIPO Einrichtungsmärkte AG
                                    </v-list-item-title>
                                    <v-list-item-subtitle style="color:#546E7A">4133 Pratteln</v-list-item-subtitle>
                                </v-list-item-content>
                            </v-list-item>
                            <div align="center" justify="center" class="text-uppercase font-weight-bold pb-2"><a
                                    style="color:#2196F3">anschauen & bewerben</a></div>
                        </v-card>
                    </v-flex>
                    <v-flex class="mt-3" xs12>
                        <v-card
                                class="white"
                        >
                            <v-img
                                    class="white--text"
                                    height="200px"
                                    :src="require('@/assets/DESKTOP/NoPath - Kopie iss.png')"
                            >
                                <v-card-title class="align-end fill-height">Crewmitarbeiter/IN</v-card-title>
                            </v-img>


                            <v-list-item three-line>
                                <v-list-item-avatar
                                        size="80"
                                        tile
                                >
                                    <v-img :src="require('@/assets/DESKTOP/NoPath.png')"></v-img>
                                </v-list-item-avatar>
                                <v-list-item-content class="align-self-start mt-3">
                                    <v-list-item-title
                                            class="headline mb-2"
                                            style="color:#546E7A"
                                    >ISS Facility Services AG
                                    </v-list-item-title>
                                    <v-list-item-subtitle style="color:#546E7A">4126 Bettingen</v-list-item-subtitle>
                                </v-list-item-content>
                            </v-list-item>
                            <div align="center" justify="center" class="text-uppercase font-weight-bold pb-2"><a
                                    style="color:#2196F3">anschauen & bewerben</a></div>
                        </v-card>
                    </v-flex>
                </v-layout>

            </v-col>

        </v-row>
        <v-row
                v-if="$vuetify.breakpoint.xs"
                justify="center"
                class="mb-5"
        >
            <v-col lg="9" class="py-0">
                <v-card
                        class="mx-auto bottomCard"
                >
                    <v-img
                            :src="require('@/assets/DESKTOP/NoPath - Kopie mcd.png')"
                            height="170px"
                            contain
                    >
                        <v-card-title
                                class="fill-height align-end text--white"
                        >Crewmitarbeiter/IN
                        </v-card-title>
                    </v-img>
                    <v-list-item three-line>
                        <v-list-item-avatar
                                size="80"
                                tile
                        >
                            <v-img :src="require('@/assets/DESKTOP/NoPath-1.png')"></v-img>
                        </v-list-item-avatar>
                        <v-list-item-content class="align-self-start mt-3">
                            <v-list-item-title
                                    class="headline mb-2"
                                    style="color:#546E7A"
                            >McDonald's
                            </v-list-item-title>
                            <v-list-item-subtitle style="color:#546E7A">8105 Regensdorf</v-list-item-subtitle>
                        </v-list-item-content>
                    </v-list-item>
                    <div align="center" justify="center" class="text-uppercase font-weight-bold pb-2"><a
                            style="color:#2196F3">anschauen & bewerben</a></div>
                </v-card>
            </v-col>
            <v-col lg="9" class="py-0">
                <v-card
                        class="mx-auto pt-0 bottomCard"
                >
                    <v-img
                            :src="require('@/assets/DESKTOP/NoPath - Kopie senior.png')"
                            height="170px"
                            contain
                    >
                        <v-card-title
                                class="fill-height align-end text--white"
                        >Senior Accountant
                        </v-card-title>
                    </v-img>
                    <v-list-item three-line>
                        <v-list-item-avatar
                                size="80"
                                tile
                        >
                            <v-img :src="require('@/assets/DESKTOP/NoPath - Kopie-1.png')"></v-img>
                        </v-list-item-avatar>
                        <v-list-item-content class="align-self-start mt-3">
                            <v-list-item-title
                                    class="headline mb-2"
                                    style="color:#546E7A"
                            >LIPO Einrichtungsmärkte AG
                            </v-list-item-title>
                            <v-list-item-subtitle style="color:#546E7A">4133 Pratteln</v-list-item-subtitle>
                        </v-list-item-content>
                    </v-list-item>
                    <div align="center" justify="center" class="text-uppercase font-weight-bold pb-2"><a
                            style="color:#2196F3">anschauen & bewerben</a></div>
                </v-card>
            </v-col>
            <v-col lg="9" class="py-0">
                <v-card
                        class="mx-auto pt-0 bottomCard"
                >
                    <v-img
                            :src="require('@/assets/DESKTOP/NoPath - Kopie iss.png')"
                            height="170px"
                            contain
                    >
                        <v-card-title
                                class="fill-height align-end text--white"
                        >Hauswart (m/w)
                        </v-card-title>
                    </v-img>
                    <v-list-item three-line>
                        <v-list-item-avatar
                                size="80"
                                tile
                        >
                            <v-img :src="require('@/assets/DESKTOP/NoPath.png')"></v-img>
                        </v-list-item-avatar>
                        <v-list-item-content class="align-self-start mt-3">
                            <v-list-item-title
                                    class="headline mb-2"
                                    style="color:#546E7A"
                            >ISS Facility Services AG
                            </v-list-item-title>
                            <v-list-item-subtitle style="color:#546E7A">4126 Bettingen</v-list-item-subtitle>
                        </v-list-item-content>
                    </v-list-item>
                    <div align="center" justify="center" class="text-uppercase font-weight-bold pb-2"><a
                            style="color:#2196F3">anschauen & bewerben</a></div>
                </v-card>
            </v-col>

        </v-row>

        <v-row
                justify="center"
        >
            <v-col lg="9" class="py-0 px-0">
                <div class="text-center pa-2 grey font-weight-bold lighten-3"
                     style="border-radius: 5px;color: #546E7A">MERH JOBS
                </div>
            </v-col>
        </v-row>

        <v-row
                justify="center"
        >
            <v-col lg="3" class="pt-0 px-0">
                <v-card
                        class="mx-auto pt-2 bottomCard"
                >
                    <v-img
                            :src="require('@/assets/DESKTOP/SVGZeichenfläche 10.png')"
                            height="200px"
                            contain
                    >
                    </v-img>
                    <v-card-text class="pa-1">
                        <v-card-title class="cardTitle font-weight-bold pa-2" style="color: #546E7A">Schritt 1
                        </v-card-title>
                        <p class="cardText" style="color: #546E7A">Erstellen Sie Ihr Profil
                            {{$vuetify.breakpoint.xs}}
                        </p>

                    </v-card-text>
                </v-card>
            </v-col>
            <v-col lg="3" class="pt-0">
                <v-card
                        class="mx-auto pt-2 bottomCard"
                >
                    <v-img
                            :src="require('@/assets/DESKTOP/SVGZeichenfläche 19.png')"
                            height="200px"
                            contain
                    >
                    </v-img>

                    <v-card-text class="pa-1">
                        <v-card-title class="cardTitle font-weight-bold pa-2">Schritt 2</v-card-title>
                        <p class="cardText">Lassen Sie sich finden oder suche den passenden Jobn</p>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col lg="3" class="pt-0 px-0">
                <v-card
                        class="mx-auto pt-2 bottomCard"
                >
                    <v-img
                            :src="require('@/assets/DESKTOP/SVG02Zeichenfläche 18.png')"
                            height="200px"
                            contain
                    >
                    </v-img>

                    <v-card-text class="pa-1">
                        <v-card-title class="cardTitle font-weight-bold pa-2">Schritt 3</v-card-title>
                        <p class="cardText">Bewerben Sie sich mit einem Klick</p>
                    </v-card-text>
                </v-card>
            </v-col>
        </v-row>

    </div>
</template>
<style>
    .bottomCard {
        background: white !important;
        margin-top: 20px;
        font-size: 14px;
        width: 1185px;
    }

    .bottomCard1 {
        background: white !important;
        margin-top: 20px;
        font-size: 14px;

    }

    .cardTitle {
        font-family: Roboto;
        color: #546E7A;
        font-size: 20px;
    }

    .cardText {
        color: #546E7A;
        margin-left: 9px;
        font-size: 12px;
    }

    a {
        align-items: center;
    }

    @media (max-width: 1074px) {

    }

    @media (max-width: 678px) {
        .bottomCard {
            max-width: 360px;
        }
    }
</style>
