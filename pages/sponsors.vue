<template>

  <v-layout row>
    <v-flex xs12 sm12 offset-sm0>
      <v-container fluid grid-list-md>
        <h2>Sponsors in 2017</h2>
        <v-layout row wrap>
          <v-flex xs12 md4 v-for="card in cards" :key="card.title" >
            <v-card class="white--text" style="padding: 10px">
              <v-card-media :src="card.src" :height="card.height" contain></v-card-media>
            </v-card>
          </v-flex>
        </v-layout>
      </v-container>
    </v-flex>
  <v-spacer></v-spacer>
  </v-layout>
</template>

<script>
  export default {
    head: {
      title: 'Sponsors'
    },
    data: () => ({
      cards: [
        { src: 'goagile.jpg', flex: 4, height: '100px' },
        { src: 'forca.png', flex: 4, height: '100px' },
        { src: 'nordea.png', flex: 4, height: '100px' }
      ]
    })
  }
</script>
