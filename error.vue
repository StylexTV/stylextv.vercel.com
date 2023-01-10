<template>
  <div>
    <NuxtLayout>
      <AppLoadingIndicator/>

      <AppContent>
        <ErrorHero :error="error"/>
      </AppContent>
      
    </NuxtLayout>
  </div>
</template>

<script setup>
useHead({
  title: 'Page not found | StylexTV'
});

const props = defineProps({
  error: Object
});
</script>
