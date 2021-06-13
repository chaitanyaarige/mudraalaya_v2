<template>
  <div class="Navbar__navbar-container">
    <v-app-bar
      class="Navbar__main-container"
      fixed
      shrink-on-scroll
      prominent
      src="/img/nav_bg.jpg"
      fade-img-on-scroll
      dark
      flat
    >
      <template #extension>
        <v-toolbar-items class="Navbar__info-icons">
          <!-- <v-btn
            color="#3b5998"
            icon
            href="https://www.facebook.com/mudraalaya.printers"
            target="_blank"
          >
            <v-icon>mdi-facebook-box</v-icon>
          </v-btn> -->
          <v-btn
            color="green"
            icon
            href="https://wa.me/919848877829"
          >
            <v-icon>mdi-whatsapp</v-icon>
          </v-btn>
          <v-btn color="lightgrey" icon href="mailto:mudraalayaprinters@gmail.com">
            <v-icon>mdi-email</v-icon>
          </v-btn>
          <v-btn color="success" icon href="tel:+919848877829">
            <v-icon>mdi-phone</v-icon>
          </v-btn>
        </v-toolbar-items>
      </template>

      <v-toolbar-title class="Navbar__logo-text">
        <img src="/img/logo_white.png" class="Navbar__logo-img" />
      </v-toolbar-title>

      <v-spacer></v-spacer>

      <v-toolbar-items class="Navbar__nav-links">
        <v-btn class="font-weight-light font-italic" text to="/">Home</v-btn>
        <v-btn class="font-weight-light font-italic" text to="/about">About</v-btn>
        <v-btn class="font-weight-light font-italic" text to="/services">Services</v-btn>
        <v-btn class="font-weight-light font-italic" text to="/user-reviews">User Reviews</v-btn>
        <v-btn class="font-weight-light font-italic" text to="/contact-us">Contact us</v-btn>
      </v-toolbar-items>

      <v-toolbar-items class="Navbar__nav-links-mobile">
        <v-menu
          transition="slide-x-transition"
          bottom
          right
          z-index="2000"
        >
          <template v-slot:activator="{ on }">
            <v-btn
              color="white"
              icon
              dark
              v-on="on"
            >
              <v-icon>mdi-menu</v-icon>
            </v-btn>
          </template>

          <v-list>
            <v-list-item to="/">
              <v-list-item-title class="font-weight-light font-italic">Home</v-list-item-title>
            </v-list-item>
            <v-list-item to="/about">
              <v-list-item-title class="font-weight-light font-italic">About</v-list-item-title>
            </v-list-item>
            <v-list-item to="/services">
              <v-list-item-title class="font-weight-light font-italic">Services</v-list-item-title>
            </v-list-item>
            <v-list-item to="/user-reviews">
              <v-list-item-title class="font-weight-light font-italic">User Reviews</v-list-item-title>
            </v-list-item>
            <v-list-item to="/contact-us">
              <v-list-item-title class="font-weight-light font-italic">Contact us</v-list-item-title>
            </v-list-item>
          </v-list>
        </v-menu>
      </v-toolbar-items>
    </v-app-bar>
  </div>
</template>

<style lang="scss">
.Navbar {
  &__navbar-container {
    z-index: 1000;
    display: inline;
  }

  &__main-container {
    z-index: 1000;
    background-image: linear-gradient(
      120deg,
      rgb(0, 0, 0) 30%,
      rgb(80, 78, 78) 70%
    );
  }

  &__nav-links {
    @media screen and (max-width: 900px) {
      display: none;
    }
  }

  &__info-icons {
    width: 80%;
    direction: rtl;
    margin: auto;
    @media screen and (max-width: 1150px) {
      width: 100%;
    }
    @media screen and (min-width: 1920px) {
      width: 1920px;
    }
  }

  &__logo-img {
    width: 300px;
    padding-bottom: 0;
    transition: all 0.3s
  }

  @media screen and (min-width: 900px) {
    &__nav-links-mobile {
      display: none;
    }
  }

  @media screen and (max-width: 900px) {
    &__nav-links-mobile {
      display: block;
    }
  }
}

.v-toolbar__content {
  width: 80%;
  margin: auto;
  @media screen and (max-width: 1150px) {
    width: 100%;
  }
  @media screen and (min-width: 1920px) {
    width: 1920px;
  }
}

.v-app-bar.v-toolbar--prominent.v-app-bar--shrink-on-scroll.v-app-bar--is-scrolled:not(.v-app-bar--bottom)
  .v-toolbar__title {
  padding-bottom: 0;
}

.v-app-bar--is-scrolled {
  .Navbar__logo-img {
    width: 220px !important;
    padding-bottom: 0;
    transition: all 0.3s;
    position: absolute;
    bottom: -22px;
  }
}
</style>
