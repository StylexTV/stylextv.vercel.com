<template>
  <div class="w-full grid grid-cols-2">
    <BlogPostHeadText>
      <BlogPostHeadTitle>{{ post.title }}</BlogPostHeadTitle>
      <BlogPostHeadDescription>{{ post.description }}</BlogPostHeadDescription>
    </BlogPostHeadText>

    <BlogPostHeadStats/>
  </div>
</template>

<script>
export default {
  props: {
    post: Object
  }
}
</script>
