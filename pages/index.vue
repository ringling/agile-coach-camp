<template>
<v-container fluid grid-list-md>

  <v-layout row wrap>
    <v-flex xs12 md4>
      <v-card>

        <v-toolbar dark color="orange" flat>
          <v-toolbar-title>Sale opened for ACCDK 2018</v-toolbar-title>
        </v-toolbar>

        <v-card-text>

          <v-container fluid grid-list-md>
            <v-layout row wrap>
              <v-flex xs6>
                <h3 class="headline">May 31 - June 2</h3>
              </v-flex>
              <v-flex xs6>
                Dragør Badehotel<br>
                Drogdensvej 43<br>
                2791 Dragør<br>
                Denmark<br>
              </v-flex>
            </v-layout>
          </v-container>
        </v-card-text>
        <v-card-actions>
              <v-flex xs6>
                <v-btn flat color="orange" value="recent" target="_blank" href="https://www.eventbrite.com/e/accdk2018-tickets-32622618129">
                  <v-icon>receipt</v-icon>
                  <span>Buy Tickets</span>
                </v-btn>
              </v-flex>
            <v-flex xs6>
            <v-btn flat color="indigo lighten-2" value="nearby" target="_blank" href="https://www.google.com/maps/place/Copenhagen+Airporthotel+%2F+Drag%C3%B8r+Badehotel/@55.5902562,12.6710978,17z/data=!3m1!4b1!4m5!3m4!1s0x4653aa4b12df335d:0x55a344639cdb1934!8m2!3d55.5902562!4d12.6732865">
              <v-icon>place</v-icon>
              <span>Location</span>
            </v-btn>
            </v-flex>
        </v-card-actions>
      </v-card>
    </v-flex>

    <v-flex xs12 md8>
      <v-card>
        <v-toolbar dark color="indigo lighten-2" flat>
          <v-toolbar-title>Greetings from ACCDK 2017</v-toolbar-title>
        </v-toolbar>
        <v-card-media src="accdk_2017_end.jpg" height="400px">
        </v-card-media>
        <v-card-title primary-title><div>
          <div class="subheading">Held on May 18 - May 20</div>
          <a class="fa fa-twitter" target="_blank" href="https://twitter.com/hashtag/accdk17"> Tweets for the 2017 ACCDK</a>
          </div>
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