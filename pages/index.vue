<template>
  <div class="Homepage__main-container">
    <div>
      <Carousel />
    </div>

    <v-container>
      <v-layout>
        <v-row class="pa-10">
          <v-flex xl6 lg6 md12 sm12 xs12 align-center>
            <div class="display-3 font-weight-thin primary--text">
              Visualise the Experience
            </div>
            <br><br>
            <p class="display-1 font-weight-thin">Our Experiance allows us to take designs and turn them into functional quick and creatve.</p>
          </v-flex>
          <v-flex xl6 lg6 md12 sm12 xs12 class="pa-3">
            <v-img src="/img/visual_2.jpg" :aspect-ratio="16/9"></v-img>
          </v-flex>
        </v-row>
      </v-layout>

      <v-layout align-center justify-center row fill-height>
        <v-parallax dark height="800" src="/img/parallax_1.jpg">
          <v-row align="center" justify="center" class="pa-10">
            <v-flex xl6 lg6 md12 sm12 xs12 class="pa-3">
              <v-img src="/img/powerful_design.jpg" :aspect-ratio="16/9"></v-img>
            </v-flex>
            <v-flex xl6 lg6 md12 sm12 xs12 class="pa-3" align-center>
              <div class="display-3 font-weight-thin primary--text">
                Powerful Design
              </div>
              <br><br>
              <p class="display-1 font-weight-thin">We make the designs with atmost care and prosperity which makes us always Proud.</p>
            </v-flex>
          </v-row>
        </v-parallax>
      </v-layout>

      <v-layout>
        <v-row class="pa-10">
          <v-flex xl6 lg6 md12 sm12 xs12 class="pa-3" align-center>
            <div class="display-3 font-weight-thin primary--text">
              Cost Effective
            </div>
            <br><br>
            <p class="display-1 font-weight-thin">We give the services at effective cost. We are best in market to provide products in budget.</p>
          </v-flex>
          <v-flex xl6 lg6 md12 sm12 xs12 class="pa-3">
            <v-img src="/img/cost_effective.jpg" :aspect-ratio="16/9"></v-img>
          </v-flex>
        </v-row>
      </v-layout>

      <v-layout align-center justify-center row fill-height>
        <v-parallax dark height="800" src="/img/parallax_1.jpg">
          <v-row align="center" justify="center" class="pa-10">
            <v-flex xl6 lg6 md12 sm12 xs12 class="pa-3">
              <v-img src="/img/visualise_1.jpg" :aspect-ratio="16/9"></v-img>
            </v-flex>
            <v-flex xl6 lg6 md12 sm12 xs12 class="pa-3">
              <div class="display-3 font-weight-thin primary--text">
                Visualise the Experience
              </div>
              <br><br>
              <p class="display-1 font-weight-thin">Our Experiance allows us to take designs and turn them into functional quick and creatve.</p>
            </v-flex>
          </v-row>
        </v-parallax>
      </v-layout>
    </v-container>
  </div>
</template>

<script>
import Carousel from '~/components/carousel/carousel'

export default {
  head: {
    titleTemplate: 'Mudraalaya Graphics & Printers',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },

      // hid is used as unique identifier. Do not use `vmid` for it as it will not work
      { hid: 'home-page', name: 'home', content: 'home description' }
    ]
  },

  components: {
    Carousel
  }
}
</script>

<style lang="scss">
.Homepage {
  &__information-section {
    width: 80%;
    margin: auto;
  }
}
</style>
