<template>
  <div>
    <div class="home">
      <home-header></home-header>
    </div>
    <!--<router-link to="/list" class="home">列表页</router-link>-->
  </div>
</template>
<script>
import HomeHeader from './components/Header'
export default {
  name: 'Home',
  components: {
    HomeHeader
  }
}
</script>
<style>
</style>
