<template>
  <NuxtLink :to="linkTo">
    <Button class="px-7 py-3 transition text-base text-white bg-gray-600 bg-opacity-80 hover:bg-opacity-100">
      Visit my GitHub
    </Button>
  </NuxtLink>
</template>

<script>
export default {
  data() {
    return {
      linkTo: 'https://github.com/stylextv'
    }
  }
}
</script>
