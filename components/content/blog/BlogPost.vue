<template>
  <BlogPostCover :post="post"/>
  <BlogPostNavbar :post="post"/>

  <AppContentItem class="flex flex-col items-center">
    <BlogPostHead :post="post"/>
    <BlogPostContent :post="post"/>
  </AppContentItem>
</template>

<script>
export default {
  props: {
    post: Object
  }
}
</script>
