<template>
  <div>
    <div class="my-4 container mx-auto max-w-screen-md">
      <h2
        class="text-3xl font-semibold mx-6 my-4 leading-none tracking-tighter"
      >
        My first Blog Post with title around 12 words which is awesome.
      </h2>
      <p class="mx-6 leading-tight tracking-tighter my-2 text-md font-semibold">
        Simply dummy text of the printing and typesetting industry. Lorem Ipsum
        has been the industry's standard dummy text ever since the 1500s, when
        an unknown printer took a galley of type and scrambled it to make a type
        specimen book. It has survived not only five centuries, but also the
        leap into electronic typesetting, remaining essentially unchanged.
      </p>
      <p class="mx-6 leading-tight tracking-tighter my-2 text-md font-semibold">
        Simply dummy text of the printing and typesetting industry. Lorem Ipsum
        has been the industry's standard dummy text ever since the 1500s, when
        an unknown printer took a galley of type and scrambled it to make a type
        specimen book. It has survived not only five centuries, but also the
        leap into electronic typesetting, remaining essentially unchanged.
      </p>
      <p class="mx-6 leading-tight tracking-tighter my-2 text-md font-semibold">
        Simply dummy text of the printing and typesetting industry. Lorem Ipsum
        has been the industry's standard dummy text ever since the 1500s, when
        an unknown printer took a galley of type and scrambled it to make a type
        specimen book. It has survived not only five centuries, but also the
        leap into electronic typesetting, remaining essentially unchanged.
      </p>
      <p class="mx-6 leading-tight tracking-tighter my-2 text-md font-semibold">
        Simply dummy text of the printing and typesetting industry. Lorem Ipsum
        has been the industry's standard dummy text ever since the 1500s, when
        an unknown printer took a galley of type and scrambled it to make a type
        specimen book. It has survived not only five centuries, but also the
        leap into electronic typesetting, remaining essentially unchanged.
      </p>
      <p class="mx-6 leading-tight tracking-tighter my-2 text-md font-semibold">
        Simply dummy text of the printing and typesetting industry. Lorem Ipsum
        has been the industry's standard dummy text ever since the 1500s, when
        an unknown printer took a galley of type and scrambled it to make a type
        specimen book. It has survived not only five centuries, but also the
        leap into electronic typesetting, remaining essentially unchanged.
      </p>
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
p {
  text-indent: 2em;
}
</style>