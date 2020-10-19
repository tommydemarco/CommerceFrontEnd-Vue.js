<template>
  <div>
    <the-header></the-header>
    <Nuxt />
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader.vue'
export default {
  components: {
    TheHeader
  }
  
}
</script>

<style>
@import url('https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css');
</style>
