<template>
  <v-footer padless dark>
    <v-card class="flex container" flat tile>
      <v-card-title class="teal">
        <!-- <strong class="subheading">Get connected with us on social networks!</strong> -->
        <v-spacer></v-spacer>
        <v-btn v-for="icon in icons" :key="icon" class="mx-4" icon>
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
        <div style="width: 20px;"></div>
      </v-card-title>

      <v-card-text class="py-2 white--text text-center">
        <p>&copy;2021 - <strong>D'sire</strong></p>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data() {
    return {
      icons: ['mdi-facebook', 'mdi-twitter', 'mdi-instagram'],
    };
  },
};
</script>

<style>
/* .footerClass {
    background-color: secondary;
} */
</style>
