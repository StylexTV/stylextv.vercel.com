<template>
  <Image :page="post._path" path="cover.jpg" class="w-full aspect-[4] object-cover shadow-lg dark:shadow-black/40"/>
</template>

<script>
export default {
  props: {
    post: Object
  }
}
</script>
