<template>
  <div>
    <Nav />
    <v-main>
      <div>
        <nuxt />
      </div>
    </v-main>
    <Section />
    <Footer />
  </div>
</template>

<script>
import Nav from '@/components/Nav.vue';
import Footer from '@/components/Footer.vue';
export default {
  components: {
    Nav,
  },
};
</script>

<style>
body {
  font-family: 'poppins';
}
.container {
  width: 100%;
  min-width: 1400px;
  box-sizing: border-box;
}
</style>
