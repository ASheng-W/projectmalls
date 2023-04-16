<template>
  <div id="app">
    <router-view></router-view>
    <MainTabBarVue></MainTabBarVue>
  </div>
</template>


<script>
  import MainTabBarVue from '@/components/content/mainTabbar/MainTabBar.vue';

export default {
  name: 'App',
  components: {
    MainTabBarVue,
  }
}
</script>


<style>

@import "assets/css/base.css"

</style>
