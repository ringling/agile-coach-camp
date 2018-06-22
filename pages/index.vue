<template>


<v-container fluid grid-list-md>
    <v-layout row wrap>

      <!-- small cards -->
      <v-flex d-flex xs12 sm6 md4>
        <v-layout row wrap>
          <v-flex d-flex>
            <v-layout row wrap class="event-card">

              <v-flex d-flex xs12>
                <v-card>
                  <v-toolbar color="blue-grey lighten-5" flat>
                    <v-toolbar-title>ACCDK 2019 on May 23-25
                    </v-toolbar-title>
                  </v-toolbar>
                  <v-card-text>

                    <v-container fluid grid-list-md>
                      <v-layout row wrap class="text-xs-center">
                        <v-flex xs6>
                          <div class="subheading">Sales opens on</div>
                          <div class="headline">January 31</div>
                          <div class="subheading">2019</div>
                        </v-flex>
                        <v-flex xs6>
                          <b>Dragør Badehotel</b><br>
                          Drogdensvej 43<br>
                          2791 Dragør<br>
                          Denmark<br>
                        </v-flex>
                      </v-layout>
                    </v-container>
                  </v-card-text>
                  <v-card-actions>
                    <v-layout row wrap class="text-xs-center">
                      <v-flex xs12>
                        <v-btn flat color="indigo lighten-2" value="nearby" target="_blank" href="https://www.google.com/maps/place/Copenhagen+Airporthotel+%2F+Drag%C3%B8r+Badehotel/@55.5902562,12.6710978,17z/data=!3m1!4b1!4m5!3m4!1s0x4653aa4b12df335d:0x55a344639cdb1934!8m2!3d55.5902562!4d12.6732865">
                          <v-icon>place</v-icon>
                          <span>Google Maps</span>
                        </v-btn>
                      </v-flex>
                    </v-layout>
                  </v-card-actions>
                </v-card>
              </v-flex>


              <v-flex d-flex xs12>
                <v-card>
                  <v-toolbar color="blue-grey lighten-5" flat>
                    <v-toolbar-title>2018 sponsors</v-toolbar-title>
                  </v-toolbar>
                  <v-card-text>
                    <v-container fluid grid-list-md>
                      <v-layout row wrap class="text-xs-center">
                        <v-flex xs6 >
                          <img class="sponsor-logo-tiny" src="goagile-tiny.jpg"></img>
                        </v-flex>
                        <v-flex xs6 >
                          <img class="sponsor-logo-tiny" style="max-width: 150px" src="zenit.png"></img>
                        </v-flex>
                        <v-flex xs6 >
                          <img class="sponsor-logo-tiny" src="ugilic.png"></img>
                        </v-flex>
                        <v-flex xs6 >
                          <img class="sponsor-logo-tiny" src="kmd.png"></img>
                        </v-flex>
                      </v-layout>
                    </v-container>
                  </v-card-text>
                </v-card>
              </v-flex>
              <v-flex d-flex xs12>
                <v-card>
                  <v-toolbar color="blue-grey lighten-5" flat>
                    <v-toolbar-title>2019 sponsors</v-toolbar-title>
                  </v-toolbar>
                  <v-card-text>
                    <v-container fluid grid-list-md>
                      <v-layout row wrap class="text-xs-center">
                        <v-flex xs12 >
                          <div class="headline orange--text">There is room for sponsors</div>
                        </v-flex>
                      </v-layout>
                    </v-container>
                  </v-card-text>
                </v-card>
              </v-flex>
            </v-layout>
          </v-flex>
        </v-layout>
      </v-flex>

      <!-- big card -->
      <v-flex d-flex xs12 sm6 md8>
        <v-card>
          <v-toolbar color="blue-grey lighten-5" flat>
            <v-toolbar-title>Greetings from ACCDK 2018</v-toolbar-title>
          </v-toolbar>
          <a href="https://www.youtube.com/watch?v=vhBuiyk7rZU" target="_blank">
            <v-card-media src="youtube.jpg" height="550px"></v-card-media>
          </a>
          <v-card-title primary-title>
            <v-layout row wrap class="text-xs-center">
              <v-flex xs6>
                <div class="subheading">Held on May 31 - June 2</div>
              </v-flex>
              <v-flex xs6>
                <a target="_blank" href="https://twitter.com/hashtag/accdk18">2018 ACCDK Tweets</a>
              </v-flex>
            </v-layout>
          </v-card-title>
        </v-card>
      </v-flex>


    </v-layout>
  </v-container>


</template>
<script>
  export default {
    head: {
      title: 'Home'
    },
    data: () => ({
      lorem: `Lorem ipsum dolor sit amet, mel at clita quando. Te sit oratio vituperatoribus, nam ad ipsum posidonium mediocritatem, explicari dissentiunt cu mea. Repudiare disputationi vim in, mollis iriure nec cu, alienum argumentum ius ad. Pri eu justo aeque torquatos.`
    })
  }
</script>

<style scoped>
  .sponsor-logo-tiny {
    max-width: 100px;
    margin: 5px;
  }


</style>

