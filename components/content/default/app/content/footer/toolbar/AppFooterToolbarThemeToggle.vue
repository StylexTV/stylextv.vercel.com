<template>
  <AppFooterToolbarItem @click="onClick">
    Awards

    <Icon name="award" class="w-6 h-6"/>
  </AppFooterToolbarItem>
</template>

<script setup>
const { toggleTheme } = useTheme();

const onClick = () => toggleTheme();
</script>
