<template>
  <div class="max-w-xl mx-auto font-mono">
    <h1 class="text-center text-5xl tracking-tighter font-bold pb-2 pt-4">
      <nuxt-link to="/"> Late Yet Eternal </nuxt-link>
    </h1>
    <hr class="border-4px mx-6 border-black" />
    <Nuxt />
    <main-footer />
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
import MainFooter from '~/components/MainFooter.vue'
export default Vue.extend({
  components: { MainFooter },
})
</script>
<style>

</style>