<template>
  <div class="Contact__main-container">
    <div class="Contact__wrapper-banner">
      <div class="Contact__main-title">
        <div class="text-center py-8">
          <span class="display-3 font-weight-thin primary--text">
            Get in touch with us
          </span>
        </div>
        <div class="Contact__main-left">
          <div class="card">
            <span class="display-3 font-weight-thin purple--text">
              Contact Information
            </span>
            <br><br>
            <div class="headline font-weight-thin success--text">
              Phone
            </div>
            <div class="headline font-weight-thin">
              +91 98488 77829
            </div>
            <div class="headline font-weight-thin">
              +91 63000 67461
            </div>
            <div class="headline font-weight-thin">
              +91 98480 91911
            </div>
            <br>
            <div class="headline font-weight-thin secondary--text">
              Email
            </div>
            <div class="headline font-weight-thin">
              mudraalaya@gmail.com
            </div>
            <div class="headline font-weight-thin">
              mudraalayaprinters@gmail.com
            </div>
            <br>
            <div class="headline font-weight-thin cyan--text">
              Address
            </div>
            <div class="headline font-weight-thin">
              Plot No - 96, Road No - 2, Block No - 31, Near Tata Motors,
            </div>
            <div class="headline font-weight-thin">
              Auto Nagar Bagh, Hayath Nagar
            </div>
            <div class="headline font-weight-thin">
              Rangareddy - 500070
            </div>
            <br>
            <div class="headline font-weight-thin light-green--text">
              Website
            </div>
            <div class="headline font-weight-thin">
              www.mudraalaya.com
            </div>
          </div>
        </div>
        <div class="Contact__main-left">
          <div class="card">
            <span class="display-3 font-weight-thin primary--text">
              We do
            </span>
            <br><br>
            <div
              v-for="(item, i) in weDo"
              :key="i"
              class="headline font-weight-light"
              :class="`${item.color}--text`"
            >
              {{ item.text }}
            </div>
          </div>
        </div>
      </div>
      <client-only>
        <vue-particles
          color="#dedede"
          hoverMode="grab"
          :clickEffect="false"
          :hoverEffect="true"
          :linesDistance="100"
          shapeType="edge"
          :particlesNumber="80"
        >
        </vue-particles>
      </client-only>
    </div>
  </div>
</template>

<script>
export default {
  head: {
    titleTemplate: 'Contact us - Mudraalaya Graphics & Printers',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },

      // hid is used as unique identifier. Do not use `vmid` for it as it will not work
      { hid: 'contact-us-page', name: 'contact-us', content: 'contact us description' }
    ]
  },

  data () {
    return {
      weDo: [
        { color: 'red', text: 'Brochures' },
        { color: 'cyan', text: 'Flyers' },
        { color: 'light-green', text: 'Business cards' },
        { color: 'pink', text: 'Booklets' },
        { color: 'blue', text: 'News letters' },
        { color: 'lime', text: 'Letter heads' },
        { color: 'blue-grey', text: 'Bill books' },
        { color: 'orange', text: 'Gift certificates' },
        { color: 'teal', text: 'Restaurant menu' },
        { color: 'green', text: 'Event Tickets' },
        { color: 'pink', text: 'Labels' },
        { color: 'cyan', text: 'Stickers' },
        { color: 'deep-purple', text: 'Calendars' },
        { color: 'light-green', text: '& Many more...' }
      ]
    }
  }
}
</script>

<style lang="scss">
.Contact {
  &__main-container {
    height: 100%;
    // height: 100vh;
    font-family: Avenir,Helvetica,Arial,sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }

  &__wrapper-banner {
    position: relative;
    -ms-flex-align: center;
    -webkit-box-align: center;
    align-items: center;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    height: 100%;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;

    #particles-js {
      background-image: url('/img/bg.jpg');
      background-size: cover;
      opacity: 0.5;
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
  }

  &__main-title {
    color: #fff;
    z-index: 999;
    box-sizing: border-box;
    width: 80%;
    display: flex;
    justify-content: space-between;
    flex-direction: column;
    @media screen and (max-width: 768px){
      flex-direction: column;
      width: 100%;
    }
  }

  &__main-left {
    width: 90%;
    margin: auto;

    .card {
      background: rgba(27, 26, 26, 0.5);
      margin: 40px 0;
      padding: 30px 0;
    }
  }
}
</style>
