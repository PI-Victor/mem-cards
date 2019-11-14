<template>
  <v-app>
    <v-content>
      <v-container>
        <v-card align="center">
          <v-card-title center>Memory cards</v-card-title>
          <v-row class="d-flex mb-6 ">
            <span> {{ item }} </span>
          </v-row>
          <v-row>
            <v-col>
              <v-card
                elevation="8"
                class="d-flex justify-center shaped"
                height="200"
                width="300px"
                justify="center"
                padding="left"
                ><span>Test</span></v-card
              >
            </v-col>
            <v-col>
              <v-card
                elevation="8"
                class="d-flex justify-center"
                height="200px"
                width="300px"
                ><span>Test</span></v-card
              >
            </v-col>
            <v-col>
              <v-card
                elevation="8"
                class="d-flex justify-center"
                height="200px"
                width="300px"
                ><span>Test</span></v-card
              >
            </v-col>
          </v-row>
        </v-card>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "memory-cards",
  data: () => ({
    item: "Hund"
  })
};
</script>
