<template>
<v-card class="overflow-hidden" >
  <v-app-bar flat lass="px-0" >
      <v-toolbar>
  <v-menu>
          <v-btn text>>
            <nuxt-link to='/contest'><span>콘테스트</span></nuxt-link> 
          </v-btn>
          <v-btn>
            <nuxt-link to='/designer'><span>디자이너</span></nuxt-link> 
          </v-btn>
          <v-btn>
            <nuxt-link to='/reviews'><span>고객후기</span></nuxt-link> 
          </v-btn>
          <v-btn>
            <nuxt-link to='/price'><span>가격 안내</span></nuxt-link> 
          </v-btn>
  </v-menu>
      </v-toolbar>
  </v-app-bar>
</v-card>
</template>

<script>
export default {

}
</script>

<style>

</style>