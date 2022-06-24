<template>
  <section class="container">
    <h1>Hello, I am a first Nuxt/Vue app!</h1>
    <Header />
    <nuxt-link to="/users">Users</nuxt-link>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'
import Header from '~/components/Header.vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>

<style>

.container{
  margin: 0 auto;
  max-width: 1200px;
  text-align: center;
}


</style>