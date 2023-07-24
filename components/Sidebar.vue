<template>
  <v-app dark>
    <v-app-bar
      hide-on-scroll
      outlined
      :clipped-left="clipped"
      elevation="0"
      style="background-color: inherit;"
      app
    >
      <v-spacer/>
      <v-toolbar-title style="color: white">
        <h3>{{ title }}</h3>
      </v-toolbar-title>
      <v-spacer />
    </v-app-bar>
    <v-main :style="{backgroundImage: `url(${background})`}" style="background-attachment: fixed; background-position: center; background-repeat: repeat">
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import background from '~/assets/background/background.jpg'
export default {
  name: 'SidebarComponent',
  data () {
    return {
      background: background,
      clipped: false,
      title: 'Diskret matematika va matekatik mantiq'
    }
  }
}
</script>

