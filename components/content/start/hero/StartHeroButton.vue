<template>
  <NuxtLink :to="linkTo" class="mt-12 p-[2px] rounded-lg bg-gradient-to-tr from-blue-500 to-red-500">
    <Button class="transition text-white bg-gray-800 hover:bg-opacity-80">
      <StartHeroButtonIcon/>

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
