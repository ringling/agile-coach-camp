<template>

  <v-layout row>
    <v-flex xs12 sm12 offset-sm0>
      <v-toolbar>
        <v-toolbar-title>Sponsors</v-toolbar-title>
      </v-toolbar>
      <v-container fluid grid-list-md>
        <v-layout row wrap>
          <v-flex xs12 md4 v-for="card in cards" :key="card.title" >
            <v-card class="white--text" style="padding: 10px">
              <v-card-media  :src="card.src" height="100px" contain></v-card-media>
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
        { src: 'goagile.jpg', flex: 4 },
        { src: 'forca.png', flex: 4 },
        { src: 'nordea.png', flex: 4 }
      ]
    })
  }
</script>

