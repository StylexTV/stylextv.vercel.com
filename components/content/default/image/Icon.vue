<template>
  <div :style="style" class="bg-current"></div>
</template>

<script>
export default {
  props: {
    name: String
  },
  computed: {
    path() {
      return '/content/default/assets/images/icons/' + this.name + '.svg'
    },
    style() {
      return {
        webkitMaskImage: 'url(' + this.path + ')',
        maskRepeat: 'no-repeat',
        maskSize: 'cover'
      }
    }
  }
}
</script>
