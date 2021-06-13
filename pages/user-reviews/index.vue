<template>
  <div class="Userreviews__main-container">
    <div class="text-center py-8">
      <span class="display-3 font-weight-thin primary--text">
        What our clients say
      </span>
    </div>

    <div class="my-10">
      <v-card flat tile>
        <div class="px-3 py-8 text-center">
          <img src="/img/client-3.jpg" width="150" style="border-radius: 50%;"/>
          <br>
          <br>
          <span class="headline font-weight-thin">
            “ Speedy, helpful, polite service and a great product at the end, I will definitely use them again and recommend them.”
          </span>
          <br><br>
          <span class="display-1 font-weight-normal green--text">
            Lavang
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
            Restaurant
          </span>
          <br><br>
          <v-rating v-model="rating" color="orange" readonly></v-rating>
        </div>
      </v-card>
      <br><br>

      <v-card flat tile>
        <div class="px-3 py-8 text-center">
          <img src="/img/client-2.jpg" width="150" style="border-radius: 50%;"/>
          <br>
          <br>
          <span class="headline font-weight-thin">
            “ Excellent service and very efficient. I use mudraalaya.com for all my printing needs - they are reliable and provide quality products and fantastic value for money!”
          </span>
          <br><br>
          <span class="display-1 font-weight-normal green--text">
            Quawell
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
            Laboratory
          </span>
          <br><br>
          <v-rating v-model="rating" color="orange" readonly></v-rating>
        </div>
      </v-card>
      <br><br>

      <v-card flat tile>
        <div class="px-3 py-8 text-center">
          <img src="/img/client-1.jpg" width="150" style="border-radius: 50%;"/>
          <br>
          <br>
          <span class="headline font-weight-thin">
            “ I have used mudraalaya.com on and off for some years to print various business cards for our company. I have never had a problem with them.They come back to you very very quickly, the turnaround of work is very fast and very professional. I would definitely, without hesitation recommend them to anyone.”
          </span>
          <br><br>
          <span class="display-1 font-weight-normal green--text">
            Crux Diesel
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
            Generator Industry
          </span>
          <br><br>
          <v-rating v-model="rating" color="orange" readonly></v-rating>
        </div>
      </v-card>
      <br><br>

      <v-card flat tile>
        <div class="px-3 py-8 text-center">
          <img src="/img/client-4.jpg" width="150" style="border-radius: 50%;"/>
          <br>
          <br>
          <span class="headline font-weight-thin">
            “ Mudraalaya.com designer was very responsive to verify our design details to meet our requirements within their product parameters. Every effort was made to achieve the on time delivery of a quality product meeting our short deadline.”
          </span>
          <br><br>
          <span class="display-1 font-weight-normal green--text">
            CuTs & CoLLors
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
            Spa & Saloon
          </span>
          <br><br>
          <v-rating v-model="rating" color="orange" readonly></v-rating>
        </div>
      </v-card>

      <div class="px-3 py-8 text-center display-2 font-weight-thin success--text">
        And Many More Happy Customers...
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head: {
    titleTemplate: 'User Reviews - Mudraalaya Graphics & Printers',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },

      // hid is used as unique identifier. Do not use `vmid` for it as it will not work
      { hid: 'reviews-page', name: 'reviews', content: 'user reviews description' }
    ]
  },

  data () {
    return {
      rating: 5
    }
  }
}
</script>

<style lang="scss">
.Userreviews {
  &__main-container {
    width: 80%;
    margin: auto;
  }
}
</style>
