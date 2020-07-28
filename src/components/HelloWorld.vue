<template>
  <v-container>
    <h1>HelloWorld</h1>
    <v-row>
      <v-col cols="12">
        <v-row :align="alignment" :justify="justify" class="grey lighten-5" style="height: 300px;">
          <v-card v-for="n in 5" :key="n" class="ma-4 pa-6" outlined tile></v-card>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({
    alignment: "center",
    justify: "center",
  }),
};
</script>
