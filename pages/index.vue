<template>

  <v-layout row>
    <v-flex xs12 sm8 offset-sm2>

        <v-card>
          <v-card-media src="http://accdk-production.nanoapp.io/images/accdk_2017_end-91741f918ae3a6dc617df04c6604132f.jpg" height="400px">
          </v-card-media>
          <v-card-title primary-title>
            <div>
              <h3 class="headline center mb-0">ACCDK 2018 - Tickets</h3>
              <div>Ticketsale for the ACCDK 2018 now open <br>From May 31 - June 2</div>
            </div>
          </v-card-title>
          <v-card-actions>
            <v-btn flat color="orange">Buy Tickets</v-btn>
          </v-card-actions>
        </v-card>

    </v-flex>
  </v-layout>


</template>
<script>
  export default {
    head: {
      title: 'Home'
    }
  }
</script>