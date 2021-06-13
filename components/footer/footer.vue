<template>
  <div class="Footer__main-container">
    <v-footer
      dark
      padless
    >
      <v-card
        flat
        tile
        class="lighten-1 white--text text-center"
        style="width:100%"
      >

        <v-card-text class="Footer__contact-details pa-5">
          <img src="/img/bottomLogo.png" alt="Bottom Logo" width="100px" />
          <div class="display-1 font-weight-thin">Let's Talk</div>
          <div class="headline font-weight-thin">Email: mudr<b>aa</b>laya@gmail.com</div>
          <div class="headline font-weight-thin">Email: mudr<b>aa</b>layaprinters@gmail.com</div>
          <div class="headline font-weight-thin">Phones: +91 98488 77829 , 63000 66461</div>
          <div class="headline font-weight-thin">WhatsApp: +91 98488 77829</div>
        </v-card-text>

        <v-card-text>
          
          <v-btn
            class="mx-4 white--text"
            icon href="tel:+919848877829"
          >
            <v-icon>mdi-phone</v-icon>
          </v-btn>

          <v-btn
            class="mx-4 white--text"
            icon
            href="mailto:mudraalayaprinters@gmail.com"
          >
            <v-icon size="24px">mdi-email</v-icon>
          </v-btn>
          
          <v-btn
            class="mx-4 white--text"
            icon
            href="https://wa.me/919848877829"
          >
            <v-icon size="24px">mdi-whatsapp</v-icon>
          </v-btn>

          <!-- <v-btn
            class="mx-4 white--text"
            icon
            href="https://www.facebook.com/mudraalaya.printers"
            target="_blank"
          >
            <v-icon size="24px">mdi-facebook</v-icon>
          </v-btn> -->

          <!-- <v-btn
            class="mx-4 white--text"
            icon
            href="https://www.instagram.com/"
            target="_blank"
          >
            <v-icon size="24px">mdi-instagram</v-icon>
          </v-btn> -->
        </v-card-text>

        <v-divider></v-divider>

        <v-card-text class="display-5 font-weight-thin white--text pt-5 Footer__terms-conditions">
          Welcome to our website. If you continue to browse and use this website, 
          you are agreeing to comply with and be bound by the following terms and conditions of use, 
          which together with our privacy policy govern Mudraalaya's relationship with 
          you in relation to this website.
        </v-card-text>

        <v-divider></v-divider>

        <v-card-text class="white--text">
          {{ new Date().getFullYear() }} &copy; <strong>Mudraalaya</strong> All rights reserved
        </v-card-text>
      </v-card>
    </v-footer>
  </div>
</template>

<style lang="scss">
.Footer {
  &__terms-conditions {
    margin: auto;
    width: 80%;
    @media screen and (min-width: 1920px) {
      max-width: 1800px;
    }
  }
}
</style>
