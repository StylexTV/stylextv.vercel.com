<template>
  <NuxtLink @contextmenu="onRightClick" to="/">
    <Icon name="stylextv" class="w-7 h-7 text-white-50"/>
  </NuxtLink>
</template>

<script>
export default {
  methods: {
    onRightClick(event) {
      event.preventDefault();

      navigateTo('/design');
    }
  }
}
</script>
