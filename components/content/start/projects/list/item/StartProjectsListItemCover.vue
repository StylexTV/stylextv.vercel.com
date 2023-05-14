<template>
  <div class="w-60 h-60 aspect-square">
    <Image page="start" :path="path" :style="style" class="w-full h-full object-cover"/>
  </div>
</template>

<script>
export default {
  props: {
    project: String
  },
  computed: {
    path() {
      return 'projects/' + this.project + '.jpg'
    },
    style() {
      return {
        clipPath: 'polygon(100% 0, 100% 100%, 0 100%, 10% 0)'
      }
    }
  }
}
</script>
