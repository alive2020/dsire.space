<template>
<v-card class="overflow-hidden container" >
  <v-app-bar flat lass="px-0" >
      <v-toolbar>
        <!-- <v-app-bar-nav-icon class="grey--text" @click="drawer = !drawer"></v-app-bar-nav-icon> -->
        <v-toolbar-title class="text-uppercase grey--text">
          <nuxt-link to='/'>
          <span>D'sire</span>
          </nuxt-link>
        </v-toolbar-title>
        <!-- <v-menu> -->
          <v-btn text>
            <nuxt-link to='/contest'><span>콘테스트</span></nuxt-link> 
          </v-btn>
          <v-btn text>
            <nuxt-link to='/designer'><span>디자이너</span></nuxt-link> 
          </v-btn>
          <v-btn text>
            <nuxt-link to='/reviews'><span>고객후기</span></nuxt-link> 
          </v-btn>
          <v-btn text>
            <nuxt-link to='/price'><span>가격 안내</span></nuxt-link> 
          </v-btn>
  <!-- </v-menu> -->
                          <!-- <Menu /> -->
        <v-spacer></v-spacer>
        <v-btn rounded>
          <nuxt-link to='/newContest'><span>콘테스트 계최하기</span></nuxt-link> 
        </v-btn>
        <v-btn text>
          <nuxt-link to='/login'><span>로그인</span></nuxt-link> 
        </v-btn>
          <v-btn text>
          <nuxt-link to='/signup'><span>회원가입</span></nuxt-link> 
          </v-btn>
        
        <!-- <v-navigation-drawer app v-model="drawer"
        absolute
        class="primary"
        >
        <p>test</p>
      </v-navigation-drawer> -->
      </v-toolbar>
      
  </v-app-bar>
</v-card>
</template>

<script>
import Menu from '@/components/Menu.vue'
export default {
components: {
    Menu
  },
  data(){
    return {
      drawer: false
    }
  }
}

</script>

<style>

</style>