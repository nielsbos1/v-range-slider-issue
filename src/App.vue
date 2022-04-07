<template>
  <v-app>
    <v-main>
      <v-container>
      <v-row>
        <v-col cols="3">
          <v-range-slider></v-range-slider>
          <!-- <v-slider></v-slider> Uncomment this and the v-range-slider will display correctly -->  
          <!-- <v-range-slider></v-range-slider> Uncomment this and the v-range-slider will still display incorrectly -->
          
        </v-col>
      </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  data: () => ({
    //
  }),
}
</script>
