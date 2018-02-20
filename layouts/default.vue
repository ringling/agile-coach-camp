<template>
  <v-app light>
    <v-navigation-drawer
      clipped
      fixed
      v-model="drawer"
      app
    >
      <v-list dense>
        <v-list-tile v-for="item in menuItems" :key="item.link">
          <v-list-tile-action>
            <v-icon >{{item.icon}}</v-icon>
          </v-list-tile-action>
          <v-list-tile-content>
            <v-list-tile-title>
              <nuxt-link :to="item.link">{{item.title}}</nuxt-link>
            </v-list-tile-title>
          </v-list-tile-content>
        </v-list-tile>

      </v-list>
    </v-navigation-drawer>

    <v-toolbar class="elevation-0 indigo lighten-2 white--text">
      <v-toolbar-side-icon @click.native.stop="drawer = !drawer" class="hidden-sm-and-up white--text"></v-toolbar-side-icon>
      <v-toolbar-title>Agile Coach Camp</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-xs-only">
        <v-btn class="white--text" flat router :to="item.link" v-for="item in menuItems" :key="item.link">
          {{item.title}}
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>

    <v-content>
      <v-container fluid fill-height>
        <v-layout justify-center align-start>
          <v-flex>
            <nuxt/>
          </v-flex>
        </v-layout>
      </v-container>
    </v-content>
    <v-footer>
      <span class="footer-text">&copy; 2018</span>
    </v-footer>
  </v-app>
</template>

<script>
  export default {
    data: () => ({
      drawer: false,
      menuItems: [
        { icon: 'home', title: 'Home', link: '/' },
        { icon: 'people', title: 'Organizers', link: '/organizers' },
        { icon: 'event_note', title: 'Program', link: '/program' },
        { icon: 'card_giftcard', title: 'Sponsors', link: '/sponsors' }
      ]
    }),
    props: {
      source: String
    }
  }
</script>

<style lang="stylus">
  @import '~vuetify/src/stylus/main'

  .footer-text
    margin-left: 10px
</style>