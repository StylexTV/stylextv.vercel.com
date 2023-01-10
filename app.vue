<template>
  <div>
    <NuxtLayout>
      <AppLoadingIndicator/>
      
      <AppContent>
        <AppHeader/>
        <NuxtPage/>
        <AppFooter/>
      </AppContent>
      
    </NuxtLayout>
  </div>
</template>

<script setup>
useHead({
  titleTemplate: (titleChunk) => {
    return titleChunk ? `${titleChunk} | StylexTV` : 'StylexTV';
  }
});

const maintenance = true;

if(maintenance) showError({ statusCode: 503, statusMessage: 'Site under maintenance' });
</script>
