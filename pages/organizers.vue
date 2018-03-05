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
                          <span class="title">The people behind ACCDK</span>
                          <p>Even an unconference needs organizers – and those of us putting together Agile Coach Camp Denmark love what we do.</p>
                          <p>For years, we had been talking about how to have a great Agile conference in Denmark. After attending some of the coolest conferences in Europe, we came upon the Agile Coach Camp concept, and the rest is history. In 2012, we held our first Agile Coach Camp in Denmark.</p>
                          <p>You can read more about us <a target="_blank" href="http://goagile.dk/om-os/">here</a>.</p>
                          <p>We look forward to seeing you!</p>
                        </div>
                      </v-card-title>
                    </v-flex>

                    <v-flex md6 xs12>
                      <v-card-media
                      src="organizers.jpg"
                      height="300px"
                      contain></v-card-media>
                    </v-flex>
                  </v-layout>
                </v-container>
              </v-card>
            </v-flex>


            <v-flex xs12 md4 v-for="card in cards" :key="card.title" >
              <v-card class="white--text">
                <v-container fluid grid-list-lg>
                  <v-layout row>
                    <v-flex xs7>
                      <div>
                        <div class="headline black--text">{{card.name}}</div>
                        <div v-if="card.primary" class="black--text"><b>Primary contact</b></div>
                        <div class="black--text">{{card.email}}</div>
                        <div v-if="card.phone" class="black--text">{{card.phone}}</div>
                      </div>
                    </v-flex>
                    <v-flex xs5>
                      <v-card-media v-if="card.src" :src="card.src" height="125px" contain></v-card-media>
                      <v-card-media v-if="!card.src" src="anon.svg" height="125px" contain></v-card-media>
                    </v-flex>
                  </v-layout>
                </v-container>
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
      title: 'Organizers'
    },
    methods: {
      color: (card) => {
        return (card.primary ? 'blue lighten-4' : '')
      }
    },
    data: () => ({
      cards: [
        { primary: true, email: 'louise@goagile.dk', name: 'Louise Navntoft', phone: '+ 45 27 12 38 87', src: 'prof-louise.jpg', flex: 4 },
        { primary: false, email: 'kschutter@exmar.dk', name: 'Karen Trolle Schütter', flex: 4 },
        { primary: false, email: 'to10lar@gmail.com', name: 'Tommy Larsen', flex: 4 },
        { primary: false, email: 'per@ugilic.dk', name: 'Per Beining', flex: 4 },
        { primary: false, email: 'jon.schou@nordea.com', name: 'Jon Schou', flex: 4 },
        { primary: false, email: 'martinlohmann@gmail.com', name: 'Martin Schwalbe Lohmann', flex: 4 },
        { primary: false, email: 'thomas@ringling.info', name: 'Thomas Ringling', flex: 4 }
      ]
    })
  }
</script>

