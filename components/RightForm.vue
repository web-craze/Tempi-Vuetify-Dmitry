<template>
    <v-card
            elevation="24"
            max-width="359px"
            width="359px"
            class="mx-auto card-right"
    >
        <v-form
                ref="form"
                lazy-validation
                class="pb-2"
        >
            <p class="headline text-center text-white" style="color: #546E7A">lch mochte mich jetzt <br/>kostenlos registrienren</p>
            <p class="subtitle-1 text-center text-white" style="color: #546E7A">Registrieren Sie Such mit Ihrem Social <br/>Media Konto an.
            </p>
            <div class="text-center">
                <v-btn class="ma-2 btn-ma" style="background-color:#F5F5F5; color:#546E7A; width:100%">
                    <v-icon>mdi-google</v-icon> &nbsp;&nbsp; MIT GOOGLE REGISTRAEREN
                </v-btn>
                <v-btn class="ma-2 btn-ma" style="background-color:#F5F5F5; color:#546E7A; width:100%">
                    <v-icon dark right>mdi-facebook</v-icon> &nbsp;&nbsp; MIT FACEBOOK REGISTRAEREN
                </v-btn>
            </div>


            <p class="subtitle-1 text-center text-white" style="color: #546E7A">oder registrieren Sie sich mit Ihrer E-Mail-Adresse an.</p>
            <v-text-field

                    label="Vorname"
                    required
            ></v-text-field>
            <v-text-field
                    label="Familienname"
                    required
            ></v-text-field>
            <v-text-field
                    label="Private E-mail-Adresse"
                    required
            ></v-text-field>
            <p class="subtitle-1 text-center" style="color:#546E7A;font-size:12px !important;">Sie erklären sich mit der Nutzervereinbarung, der
                Datenschutzrichtlinie und der Cookie-Richtlinie von TEMPI einverstanden. </p>
            <v-btn
                    class="vtn-login"
                    color="#2196F3"
            >
                Kostenlos Registrieren
            </v-btn>
            <p class="subtitle-1 text-center text-white pt-2 ma-0" style="color: #546E7A;font-size: 14px;">überspringen</p>

        </v-form>

    </v-card>
</template>
<style>

    .card-right {
        background: white !important;
        opacity: 0.9 !important;
    }

    .v-label {
        color: black !important;
    }

    .v-input__slot:before {
        border-color: black !important;
    }

    .v-form {
        padding: 30px;
    }

    .vtn-login {
        width: 100%;
    }

    .text-white {
        color: black;
    }

    .btn-ma {
        background-color: #F5F5F5;
        color: black
    }

    @media (max-width: 678px) {

    }
</style>



