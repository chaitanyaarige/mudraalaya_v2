<template>
  <v-app dark class="Default__layout-container">
    <Navbar />
    <div class="Default__pages-container">
      <nuxt />
    </div>
    <Footer />
    <div class="Default__scroll-top">
      <v-btn class="mx-2" fab dark small @click="scrollToTop" color="black">
        <v-icon dark class="font-weight-thin">mdi-arrow-collapse-up</v-icon>
      </v-btn>
    </div>
  </v-app>
</template>

<script>
import Navbar from '~/components/nav/navbar'
import Footer from '~/components/footer/footer'

export default {
  components: {
    Navbar,
    Footer
  },

  data () {
    return {
      offsetTop: 500
    }
  },

  methods: {
    scrollToTop () {
      this.offsetTop = 0
    }
  }
}
</script>

<style lang="scss">
.Default {
  &__pages-container {
    width: 100%;
    margin: 225px auto 0 auto;
    @media screen and (min-width: 1920px) {
      max-width: 1920px;
    }
  }

  &__scroll-top {
    display: none;
    position: fixed;
    bottom: 30px;
    right: 10px;
  }
}
</style>
