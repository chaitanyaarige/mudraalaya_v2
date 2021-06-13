<template>
  <div class="Carousel__main-container">
    <v-carousel
      continuous
      cycle
      hide-delimiter-background
      interval="4000"
      dark
      :show-arrows="false"
    >
      <!-- vertical
      vertical-delimiters -->
      <v-carousel-item src="/carousel/carousel_1.jpg">
        <v-row
          class="
            fill-height
            justify-start
            align-center
            pa-4
            d-none
            d-sm-flex
            light
          "
        >
          <div>
            <div class="display-3 black--text">
              Design simplifies
            </div>
            <div
              class="display-4 primary--text font-weight-bold"
              color="primary--text"
            >
              COMPLICATIONS
            </div>
          </div>
        </v-row>
        <!-- sm -->
        <v-row
          class="
            fill-height
            justify-start
            align-top
            pa-3
            d-flex
            d-sm-none
          "
        >
          <div>
            <div class="display-1 black--text font-weight-thin">
              Design simplifies
            </div>
            <div
              class="
                display-2
                primary--text
                font-weight-thin
              "
              color="primary--text"
            >
              COMPLICATIONS
            </div>
          </div>
        </v-row>
      </v-carousel-item>

      <v-carousel-item src="/carousel/carousel_2.jpg">
        <v-row
          class="
            fill-height
            justify-end
            align-center
            pa-4
            d-none
            d-sm-flex
          "
        >
          <div class="Carousel__second-box">
            <div class="display-3 black--text">
              Design is the silent
            </div>
            <div
              class="display-4 primary--text font-weight-bold"
              color="primary--text"
            >
              AMBASSADOR
            </div>
            <div class="display-3 black--text">
              of your deram
            </div>
          </div>
        </v-row>
        <!-- sm -->
        <v-row
          class="
            fill-height
            justify-start
            align-center
            pa-3
            d-flex
            d-sm-none
          "
        >
          <div>
            <div class="display-1 black--text font-weight-thin">
              Design is the silent
            </div>
            <div
              class="display-1 primary--text font-weight-regular"
              color="primary--text"
            >
              AMBASSADOR
            </div>
            <div class="display-1 black--text font-weight-thin">
              of your dream
            </div>
          </div>
        </v-row>
      </v-carousel-item>

      <v-carousel-item src="/carousel/carousel_3.jpg">
        <v-row
          class="
            fill-height
            justify-start
            align-center
            pa-4
            d-none
            d-sm-flex
          "
        >
          <div>
            <div class="display-3 black--text">
              Destination of your
            </div>
            <div
              class="display-4 primary--text font-weight-bold"
              color="primary--text"
            >
              COLOR
              <span
                class="display-3
                black--text"
              >
                dreams
              </span>
            </div>
          </div>
        </v-row>
        <!-- sm -->
        <v-row
          class="
            fill-height
            justify-start
            align-center
            pa-3
            d-flex
            d-sm-none
          "
        >
          <div>
            <div class="display-1 black--text font-weight-thin">
              Destination of your
            </div>
            <div
              class="display-1 primary--text font-weight-thin"
              color="primary--text"
            >
              COLOR
              <span
                class="display-1
                black--text
                font-weight-thin"
              >
                dreams
              </span>
            </div>
          </div>
        </v-row>
      </v-carousel-item>

      <v-carousel-item src="/carousel/carousel_4.jpg">
        <v-row
          class="
            fill-height
            justify-start
            align-center
            pa-4
            d-none
            d-sm-flex
          "
        >
          <div>
            <div class="display-3 white--text">
              We
              <span
                class="display-4 primary--text font-weight-bold"
                color="primary--text"
              >
                IMPRESS
              </span>
              your
            </div>
            <div
              class="display-4 primary--text font-weight-bold"
              color="primary--text"
            >
              IMPRESSIONS
            </div>
          </div>
        </v-row>
        <!-- sm -->
        <v-row
          class="
            fill-height
            justify-start
            align-center
            pa-4
            d-flex
            d-sm-none
          "
        >
          <div>
            <div class="display-1 font-weight-thin white--text">
              We
              <span
                class="display-1 primary--text font-weight-thin"
                color="primary--text"
              >
                IMPRESS
              </span>
              your
            </div>
            <div
              class="display-1 primary--text font-weight-thin"
              color="primary--text"
            >
              IMPRESSIONS
            </div>
          </div>
        </v-row>
      </v-carousel-item>
    </v-carousel>
  </div>
</template>

<style lang="scss">
.Carousel {
  &__second-box {
    background: rgba(236, 235, 235, 0.2);
    padding: 5px;
  }
}
</style>
