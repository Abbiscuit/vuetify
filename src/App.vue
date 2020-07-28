<template>
  <v-app>
    <Header />

    <v-main>
      <section
        class="hero"
        style="
        height: 30vh;
        background-color: #212121;
        color: #fff;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
      "
      >
        <h3>Build beautiful products, faster.</h3>
        <p>Material is a design system – backed by open-source code – that helps teams build high-quality digital experiences.</p>
        <div style="width: 300px; display: flex; justify-content: space-between;">
          <v-btn depressed outlined color="white">GET STARTED</v-btn>
          <v-btn depressed outlined color="white">GET STARTED</v-btn>
        </div>
      </section>
      <Resources />
    </v-main>
  </v-app>
</template>

<script>
import Header from "@/components/Header";
import Resources from "@/components/Resources";

export default {
  name: "App",

  components: {
    Header,
    Resources,
  },

  data: () => ({}),
  methods: {},
};
</script>

