<template>
  <div>
    <v-carousel height="600" :show-arrows="false">
      <v-carousel-item
        v-for="(item, i) in items"
        :key="i"
        :src="item.src"
        reverse-transition="fade-transition"
        transition="fade-transition"
      >
        <div class="showcaseText">
          <h1>Fulfill your D'sire</h1>
          <p>This is the space of your desires</p>
        </div>
      </v-carousel-item>
    </v-carousel>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          src:
            'https://images.unsplash.com/photo-1541944743827-e04aa6427c33?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1826&q=80',
        },
        {
          src:
            'https://images.unsplash.com/photo-1506806732259-39c2d0268443?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1952&q=80',
        },
        {
          src:
            'https://images.unsplash.com/photo-1477517787936-70ba786643fd?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=934&q=80',
        },
        {
          src:
            'https://images.unsplash.com/photo-1531602541797-f3141d0ced31?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1950&q=80',
        },
      ],
    };
  },
};
</script>

<style scoped>
.showcaseText {
  position: relative;
  top: 50%;
  right: 50%;
}
h1 {
  font-size: 5rem;
  color: white;
}
p {
  color: white;
}
</style>
