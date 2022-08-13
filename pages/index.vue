<script setup>
useHead({
  title: 'Emircan Erdemci',
  // or, instead:
  // titleTemplate: (title) => `My App - ${title}`,
   meta: [
    { name: 'description', content: 'Portfolio sites' },
    { name: 'keywords', content: 'HTML,CSS,JavaScript,Vue,React' },
    { name: 'author', content: 'Emircan Erdemci' },
    
  ],
  viewport: 'width=device-width, initial-scale=1, maximum-scale=1',
  charset: 'utf-8',
 
 
})
</script>
<template>
<div>
<navbar />
<me-cards  />
</div>
</template>