<template>
  <div class="About__main-container">
    <div class="px-3 py-8">
      <span class="display-3 font-weight-thin primary--text">
        About Mudraalaya
      </span>
      <br><br><br>
      <p class="headline font-weight-thin">
        Mudraalaya was established in 2017 with a vision to achieve excellence in the area of 
        Graphics and Printing. Our aim is to provide quality services to our clients every time. 
        The guiding factor for our company lies in understanding the importance of customer be it 
        an individual customer or a large corporate house. We want to provide an optimum solution 
        with utmost reliability, dedication and innovation. We treat our customers as a level playing 
        field for improving the services through continuous feedback and good governance. We cater to 
        our customer needs with personalized service to make them our repeated clients. We need an 
        opportunity to make you feel the difference. We understand the needs and demands of the market, 
        we will apply our best efforts to give quality to your current and future requirements.
      </p>
    </div>

    <v-parallax dark height="800" src="/img/parallax_2.jpg">
      <div class="About__we-do px-3 py-8 text-center">
        <span class="display-3 font-weight-thin primary--text">
          What We Do
        </span>
        <br><br><br>
        <p class="headline font-weight-thin success--text">
          Brochures
        </p>
        <p class="headline font-weight-thin orange--text">
          Letter Heads
        </p>
        <p class="headline font-weight-thin yellow--text">
          Booklets
        </p>
        <p class="headline font-weight-thin red--text">
          Stickers
        </p>
        <p class="headline font-weight-thin green--text">
          Adversiment Design
        </p>
        <p class="headline font-weight-thin cyan--text">
          Flyer Design
        </p>
        <p class="headline font-weight-thin grey--text">
          Newsletter Design
        </p>
        <p class="headline font-weight-thin red--text">
          Corporate Profile Design
        </p>
        <p class="headline font-weight-thin yellow--text">
          Hoarding Design
        </p>
        <p class="headline font-weight-thin success--text">
          Dairy Design
        </p>
        <p class="headline font-weight-thin grey--text">
          Menus Design
        </p>
        <p class="headline font-weight-thin light-green--text">
          Social Media Banners
        </p>
        <p class="headline font-weight-thin green--text">
          Printing And Delivery
        </p>
      </div>
    </v-parallax>
    <br><br>

    <div class="px-3 py-8">
      <span class="display-3 font-weight-thin primary--text">
        Our Best Propositions for You!
      </span>
      <br><br><br>
      <p class="headline font-weight-thin">
        We want to provide an optimum solution with utmost reliability, dedication and innovation. We treat our customers as a level playing field for improving the services through continuous feedback and good governance.
      </p>
    </div>
    <br><br>
  </div>
</template>

<script>
export default {
  head: {
    titleTemplate: 'About - Mudraalaya Graphics & Printers',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },

      // hid is used as unique identifier. Do not use `vmid` for it as it will not work
      { hid: 'about-page', name: 'about', content: 'about description' }
    ]
  }
}
</script>

<style lang="scss">
.About {
  &__main-container {
    width: 80%;
    margin: auto;

    @media screen and (max-width: 500px) {
      width: 100%;
      padding: 10px;
    }
  }

  &__we-do {
    p {
      &:hover {
        color: rgb(223, 171, 197);
        cursor: pointer;
        font-weight: bold;
      }
    }
  }
}
</style>
