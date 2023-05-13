<template>
  <div class="w-60 h-60 aspect-square">
    <Image page="start" :path="path" class="w-full h-full object-cover"/>
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
    }
  }
}
</script>
