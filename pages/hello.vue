<template>
  <div>
    <div v-for="post in posts" :key="post.title">
      {{ post.slug }}
    </div>
  </div>
</template>

<script>
export default {
  async asyncData({ $content }) {
    const posts = await $content('posts/en').fetch()
    return {
      posts,
    }
  },
}
</script>

<style lang="scss" scoped>
</style>