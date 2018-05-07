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
                    <v-toolbar-title>Pre- & post programs</v-toolbar-title>
                  </v-toolbar>
                  <v-card-text>
                    <v-container fluid grid-list-md>





                      <v-layout row wrap class="text-xs-center">
                        <v-flex xs6>
                          <b>Sightseeing in Copenhagen</b><br>
                          Pre-program<br>
                          <a href="https://www.linkedin.com/pulse/accdk-2018-pre-program-sightseeing-copenhagen-karen-trolle-schutter/" target="_blank">Read more on LinkedIn</a>

                        </v-flex>
                        <v-flex xs6 >
                          <b>Beer Festival</b><br>
                          Post-program<br>
                          <a href="https://www.linkedin.com/pulse/accdk-2018-post-program-beer-festival-karen-trolle-schutter/" target="_blank">Read more on LinkedIn</a>



                        </v-flex>
                      </v-layout>
                    </v-container>
                  </v-card-text>
                </v-card>
              </v-flex>
               <v-flex d-flex xs12>
                <v-card>
                  <v-toolbar color="blue-grey lighten-5" flat>
                    <v-toolbar-title>Masterclass</v-toolbar-title>
                  </v-toolbar>
                  <v-card-text>
                    <v-container fluid grid-list-md>
                      <v-layout row wrap class="text-xs-center">
                        <v-flex xs12 >
                          With <b>Karen Tobiasen</b>, Chief People Officer and Head of People at Nordea, <b>“What’s love got to do with it”</b>.
                          <br><a href="https://www.linkedin.com/pulse/accdk-whats-love-got-do-karen-trolle-schutter/" target="_blank">Read more on LinkedIn</a>
                        </v-flex>
                      </v-layout>
                    </v-container>
                  </v-card-text>
                </v-card>
              </v-flex>






              <v-flex d-flex xs12>
                <v-card>
                  <v-toolbar dark color="orange" flat>
                    <v-toolbar-title>Sale opened for ACCDK 2018</v-toolbar-title>
                  </v-toolbar>
                  <v-card-text>

                    <v-container fluid grid-list-md>
                      <v-layout row wrap class="text-xs-center">
                        <v-flex xs6>
                          <div class="headline">May 31 - June 2</div>
                          <div class="subheading">2018</div>
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
                      <v-flex xs6>
                        <v-btn flat color="orange" value="recent" target="_blank" href="https://www.eventbrite.com/e/accdk2018-tickets-32622618129">
                          <v-icon>receipt</v-icon>
                          <span>Buy Tickets</span>
                        </v-btn>
                      </v-flex>
                      <v-flex xs6>
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
                        <v-flex xs12 >
                          <img class="sponsor-logo-tiny" src="goagile-tiny.jpg"></img>
                          <div class="headline orange--text">There is room for more sponsors</div>
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
            <v-toolbar-title>Greetings from ACCDK 2017</v-toolbar-title>
          </v-toolbar>
          <v-card-media src="accdk_2017_end.jpg" height="400px"></v-card-media>
          <v-card-title primary-title>
            <v-layout row wrap class="text-xs-center">
              <v-flex xs6>
                <div class="subheading">Held on May 18 - May 20</div>
              </v-flex>
              <v-flex xs6>
                <a target="_blank" href="https://twitter.com/hashtag/accdk17">2017 ACCDK Tweets</a>
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

