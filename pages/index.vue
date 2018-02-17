<template>

  <v-layout row>
    <v-flex xs12 sm8 offset-sm2>

        <v-card>
          <v-card-media src="accdk_2017_end.jpg" height="400px">
          </v-card-media>
          <v-card-title primary-title>
            <div>
              <h3 class="headline center mb-0">ACCDK 2018  <span class="badge orange white--text">Ticket sale started</span></h3>

              <div>Ticketsale for the ACCDK 2018 now started <br>From May 31 - June 2</div>
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

<style>
  .badge{

    border: 1px solid red;
    padding: 2px 7px 2px 7px;
    border-radius: 5px 5px;

  }
</style>