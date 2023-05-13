<template>
  <DesignListItemCover :style="'background-color: ' + color" class="rounded-xl"/>
</template>

<script>
export default {
  props: {
    color: String,
    isLight: Boolean,
    isDark: Boolean
  }
}
</script>
