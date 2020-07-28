<template>
  <v-app-bar app color="grey darken-4" dark>
    <v-toolbar-title>Material Design</v-toolbar-title>

    <v-spacer></v-spacer>

    <v-btn href="https://github.com/vuetifyjs/vuetify/releases/latest" target="_blank" text>
      <span class="mr-2">Latest Release</span>
      <v-icon>mdi-open-in-new</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {
  name: "Header",
  data: () => ({
    //
  }),
};
</script>

<style>
</style>