<template>
  <div>
    <v-container fluid class="mb-5">
      <div style="padding: 0 16px;">
        <h1>Design guidance and code</h1>
        <p>Use our most popular design and development resources to jumpstart your latest project</p>
      </div>
      <v-row no-gutters>
        <v-col v-for="n in 3" :key="n" md="4" lg="4">
          <v-card class="ma-3 pa-4" outlined>
            <v-img
              src="https://lh3.googleusercontent.com/EWZvifAYMFXxRwxWa1GjXt8NrDPY39ndSav5oXHs91H5h2gPWi_lPxf3yKNXhZQCXoTGIav6nsu11iOIZ5aFSVW8MZkbPOCX5Eip=w760-h380"
            ></v-img>

            <v-card-title>Material Design guidelines</v-card-title>

            <v-card-text>
              <div>Material Design principles, styles, and best practices</div>
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
    <v-container fluid class="mb-5">
      <div style="padding: 0 16px;">
        <h1>Design guidance and code</h1>
        <p>Use our most popular design and development resources to jumpstart your latest project</p>
      </div>
      <v-row no-gutters>
        <v-col v-for="n in 3" :key="n" md="4" lg="4">
          <v-card class="ma-3 pa-4" outlined>
            <v-img
              src="https://lh3.googleusercontent.com/Gt3Y6vLTaHrDszSBOdaSX5LCkg2Cwo6oQ569V5rrs6Vw4vJV8mGBufd-SLhCmMn8KNWAQcCDRk8Hyr_3D6uh9jdvZhcQdZzTmKpCNQ=w760-h380"
            ></v-img>

            <v-card-title>Material Design guidelines</v-card-title>

            <v-card-text>
              <div>Material Design principles, styles, and best practices</div>
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>