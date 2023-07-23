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
      <v-toolbar-title>{{ title }}</v-toolbar-title>
      <v-spacer />
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'SidebarComponent',
  data () {
    return {
      clipped: false,
      title: 'Diskret matematika va matekatik mantiq'
    }
  }
}
</script>
