<template>
  <Navbar/>
  <router-view></router-view>
</template>

<script>

import Navbar from './components/Navbar.vue'

  export default{
    name: 'app',
    components: {
      Navbar
    },
  }

</script>

<style scoped>
</style>
