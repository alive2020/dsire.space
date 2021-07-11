<template>
  <div>
    <Showcase />
  </div>
</template>

<script>
import Showcase from '@/components/Showcase.vue';

export default {
  components: {
    Showcase,
  },
  head() {
    return {
      title: "About the D'sire",
      meta: [
        {
          hid: 'description',
          name: 'description',
          content:
            "D'sire is the most creative network for outsourcing and discovering creative work",
        },
        {
          hid: 'keywords',
          name: 'keywords',
          content:
            'designer platform, creative community, creative network, creative design, 디자이너 플렛폼, 디자인외주, 외주, 아트, 미술, 예술, ',
        },
      ],
    };
  },
};
</script>

<style></style>
