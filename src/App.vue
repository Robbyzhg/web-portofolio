<template>
  <div id="app">
    <Navbar />
    <Home class="mt-5" />
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Home from '@/components/Home.vue'

export default {
  name: 'App',
  components: {
    Home,
    Navbar,
  },
}
</script>

<style>
</style>
