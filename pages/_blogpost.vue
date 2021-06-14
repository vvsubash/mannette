<template>
  <div class="flex container mx-auto max-w-screen-md">
    <nav
      id="navbar"
      class="
        bg-yellow-100
        block
        fixed
        inset-x-0
        bottom-0
        z-10
        shadow
        px-2
        py-1
        md:relative
        md:top-0
        md:inset-y-0
        md:left
        md:w-48
        md:-ml-24
        md:mt-8
      "
    >
      <div class="flex justify-between text-center md:flex-col md:items-center">
        <span class=" md:mb-4">
          <outline-home-icon class="w-6 h-6" />
          <h3 class="text-xs">Home</h3>
        </span>
        <span class="md:mb-4">
          <outline-volume-up-icon class="w-6 h-6" />
          <h3 class="text-xs">Listen</h3>
        </span>
        <span class="md:mb-4">
          <outline-translate-icon class="w-6 h-6" />
          <h3 class="text-xs">Translations</h3>
        </span>
        <span class="md:mb-4">
          <outline-chat-alt2-icon class="w-6 h-6" />
          <h3 class="text-xs">Comments</h3>
        </span>
      </div>
    </nav>
    <section id="otherthannav">
    <section id="post" class="my-4">
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
    </section>
    <div id="comments">
      <h1>Comments</h1>
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
    </section>
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
