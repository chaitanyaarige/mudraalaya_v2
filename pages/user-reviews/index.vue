<template>
  <div class="Userreviews__main-container">
    <div class="text-center py-8">
      <span class="display-3 font-weight-regular primary--text">
        What our clients say
      </span>
    </div>

    <div class="my-10">
      <!--Delhi public scool -->
      <v-card flat tile>
        <div class="px-3 py-8 text-center">
          <img src="/img/DPS.jpg" width="150" style="border-radius: 50%;"/>
          <br>
          <br>
          <span class="headline font-weight-thin">
            “ We use Mudraalaya Printing for printing various needs, they always respond in a quick turnaround time, with competitive rate, good service and with a smile.

            We are very impressed with the services & speed of Mudraalaya Printers.

            Wishing you the best”
          </span>
          <br><br>
          <span class="display-1 font-weight-normal green--text">
            Robinson Michael
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
          Head - Public Relations
          </span>
          <br><br>
          <v-rating v-model="rating" color="orange" readonly></v-rating>
        </div>
      </v-card>
      <br><br>

      <!--Dilsukhnagar public school -->    
      <v-card flat tile>
        <div class="px-3 py-8 text-center">
          <img src="/img/dilpschool.jpg" width="150" style="border-radius: 50%;"/>
          <br>
          <br>
          <span class="headline font-weight-thin">
            “ More than impressed with Mudraalaya`s impeccable service and follow up. Thank you for making good on your promises.”
          </span>
          <br><br>
          <span class="display-1 font-weight-normal green--text">
            Aruna Bopanna 
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
            Exam Branch Incharge
          </span>
          <br><br>
          <v-rating v-model="rating" color="orange" readonly></v-rating>
        </div>
      </v-card>
      <br><br>


    <!--Anu Furniture -->
      <v-card flat tile>
        <div class="px-3 py-8 text-center">
          <img src="/img/anu furniture.jpg" width="150" style="border-radius: 50%;"/>
          <br>
          <br>
          <span class="headline font-weight-thin">
            “ Speedy, helpful, polite service and a great product at the end, I will definitely use them again and recommend them.”
          </span>
          <br><br>
          <span class="display-1 font-weight-normal green--text">
            E.B.Christine & Nagaraju
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
            Managers
          </span>
          <br><br>
          <v-rating v-model="rating" color="orange" readonly></v-rating>
        </div>
      </v-card>
      <br><br>

     
     <!--Deccon Hopitals -->    
      <v-card flat tile>
        <div class="px-3 py-8 text-center">
          <img src="/img/Deccan.jpg" width="150" style="border-radius: 50%;"/>
          <br>
          <br>
          <span class="headline font-weight-thin">
            “ Good Professionalized Printers perfect timing with good work. I will use and recommend the Mudraalaya Printers.”
          </span>
          <br><br>
          <span class="display-1 font-weight-normal green--text">
            Pavan  
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
           Purchase & Store Manager
          </span>
          <br><br>
          <v-rating v-model="rating" color="orange" readonly></v-rating>
        </div>
      </v-card>
      <br><br>

       <!--Tech Zert -->    
      <v-card flat tile>
        <div class="px-3 py-8 text-center">
          <img src="/img/Techzert.jpg" width="150" style="border-radius: 50%;"/>
          <br>
          <br>
          <span class="headline font-weight-thin">
            “ Customer focused, maintains great eye for detail, suggests innovative ideas to help customers. I really liked thier focus on Quality and Customer satisfaction. Looking forward for increased association with Mudraalaya!.”
          </span>
          <br><br>
          <span class="display-1 font-weight-normal green--text">
           K.S.R.K. Prasad  
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
           Vice President 
          </span>
          <br><br>
          <v-rating v-model="rating" color="orange" readonly></v-rating>
        </div>
      </v-card>
      <br><br>

     
     <!--Stone 36 -->    
      <v-card flat tile>
        <div class="px-3 py-8 text-center">
          <img src="/img/stone36.jpg" width="150" style="border-radius: 50%;"/>
          <br>
          <br>
          <span class="headline font-weight-thin">
            “ Commitment with Quality & Quantity output is what we are bounded with Mudraalaya team. Keep up the great job & wish you all the best.”
          </span>
          <br><br>
          <span class="display-1 font-weight-normal green--text">
            Hemanth Chawda
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
            STONE 36 C.E.O
          </span>
          <br><br>
          <v-rating v-model="rating" color="orange" readonly></v-rating>
        </div>
      </v-card>
      <br><br>
      
    <!--Menu 28 -->
      <v-card flat tile>
        <div class="px-3 py-8 text-center">
          <img src="/img/Menu28.jpg" width="150" style="border-radius: 50%;"/>
          <br>
          <br>
          <span class="headline font-weight-thin">
            “ Excellent service and very efficient. I use mudraalaya for all my printing needs - they are reliable and provide quality products and fantastic value for money!”
          </span>
          <br><br>
          <span class="display-1 font-weight-normal green--text">
            G Sravan Reddy
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
            GSR Hospitality , Director
          </span>
          <br><br>
          <v-rating v-model="rating4" color="orange" readonly></v-rating>
        </div>
      </v-card>
      <br><br>


    <!--Crux -->
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
           Krishh
          </span>
          <br>
          <span class="font-weight-thin yellow--text">
            Crux Diesel, Generator Industry
          </span>
          <br><br>
          <v-rating v-model="rating" color="orange" readonly></v-rating>
        </div>
      </v-card>
      <br><br>


    <!--Cuts n Collors -->
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
      <br><br>
    

     
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
      rating: 5,
      rating4: 4
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
