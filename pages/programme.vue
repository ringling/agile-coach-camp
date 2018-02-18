<template>
  <v-layout column>
    <v-flex xs12 sm12 offset-sm0>

        <v-container fluid grid-list-md>
          <v-layout row wrap>

            <v-flex xs12 md12>
              <v-card>
                <v-container fluid>
                  <v-layout row wrap>
                    <v-flex md6 xs12>
                      <v-card-title>
                        <div>
                          <span class="title">Open Space</span>
                            <p>
                              The Agile Coach Camp is an Open Space/unconference event and provides a simple mean to self-organize.
                            </p>
                            There are four principals to have in mind for an Open Space event:
                            <ol style="margin-left:13px">
                              <li> Whoever comes is the right people.</li>
                              <li> Whatever happens is the only thing that could have.</li>
                              <li> When it starts is the right time.</li>
                              <li> When it's over it's over.</li>
                            </ol>

                        </div>
                      </v-card-title>
                    </v-flex>

                    <v-flex md6 xs12>
                      <v-card-media
                      src="programme.jpg"
                      height="300px"
                      contain></v-card-media>
                    </v-flex>
                  </v-layout>
                </v-container>
              </v-card>
            </v-flex>

          </v-layout>

          <h2>2018 - To be announced</h2>
          <h2>2017 - Last years programme</h2>
          <v-layout row wrap>

             <v-flex xs12 md4>
              <v-card>
                <v-card-title primary-title>

                  <div style="margin-left:13px">
                  <div class="title">The 18th</div><br>
                    <ul class="list-unstyled">
                      <li><b>16.00</b> Welcome - snacks and soda</li>
                      <li><b>16.30</b> Opening &amp; market place</li>
                      <li><b>18.00-18.55</b> Session</li>
                      <li><b>19.05-19.55</b> Sessions</li>
                      <li><b>20.00-20.20</b> Output &amp; presentation</li>
                      <li><b>20.25</b> Dinner</li>
                      <li>Yoga or ???</li>
                    </ul>
                  </div>
                </v-card-title>
              </v-card>
            </v-flex>

            <v-flex xs12 md4>
              <v-card>
                <v-card-title primary-title>

                  <div style="margin-left:13px">
                    <div class="title">The 19th</div><br>
                    <ul class="list-unstyled">
                      <li><b>07.30</b> Good morning workout</li>
                      <li><b>08.30</b> Breakfast/shower</li>
                      <li><b>09.00</b> Market place</li>
                      <li><b>09.30-10.25</b> Sessions</li>
                      <li><b>10.30-11.25</b> Sessions</li>
                      <li><b>11.30-12.00</b> Output &amp; presentations</li>
                      <li><b>12.00</b> Lunch</li>
                      <li><b>12.45-13.45</b> Sessions</li>
                      <li><b>13.50-14.45</b> Sessions</li>
                      <li><b>14.50-15.25</b> Sessions</li>
                      <li><b>15.30-16.00</b> Output &amp; presentation</li>
                      <li><b>16:00</b> Coffee/tea</li>
                      <li><b>16.20-17.30</b> Sessions</li>
                      <li><b>17.35-18.25</b> Sessions</li>
                      <li><b>18.30-19.00</b> Output &amp; presentation</li>
                      <li><b>19.30</b> Dinner</li>
                      <li><b>22.00</b> - What do you feel like… Bring games and ideas <i class="fa fa-smile-o"></i></li>
                    </ul>
                  </div>
                </v-card-title>
              </v-card>
            </v-flex>



             <v-flex xs12 md4>
              <v-card>
                <v-card-title primary-title>

                  <div style="margin-left:13px">
                    <div class="title">The 20th</div><br>
                    <ul class="list-unstyled">
                      <li><b>07.30</b> Good morning workout</li>
                      <li><b>08.30</b> Breakfast/shower</li>
                      <li><b>09.00</b> Look at Market place</li>
                      <li><b>09.30–10.25</b> Sessions</li>
                      <li><b>10.30-11.25</b> Sessions</li>
                      <li><b>11.30-12.00</b> Output &amp; presentation</li>
                      <li><b>12.00</b> Closing ACCDK2017 - Group hug and goodbye or see you <i class="fa fa-smile-o"></i></li>
                      <li><b>13.30</b> Lunch for those who wants</li>
                    </ul>
                  </div>
                </v-card-title>
              </v-card>
            </v-flex>


          </v-layout>


        </v-container>

    </v-flex>
  </v-layout>
</template>

<script>
  export default {
    head: {
      title: 'Program'
    },
    methods: {
      color: (card) => {
        return (card.primary ? 'blue lighten-4' : '')
      }
    },
    data: () => ({
    })
  }
</script>

