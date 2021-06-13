<template>
  <div>
    <div>
        <h2>My first Blog Poast with title around 12 words </h2>
    </div>
    <nav-bar-post-page />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import NavBarPostPage from '~/components/NavBarPostPage.vue'

export default Vue.extend({
  components: { NavBarPostPage },
})
</script>

<style scoped>
</style>