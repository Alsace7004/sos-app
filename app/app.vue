<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup lang="ts">
  useHead({
    title: "ÉcouteSolidaire - Plateforme d'écoute psychologique",
    meta: [
      { name: 'description', content: "Plateforme d'écoute psychologique." },
    ],
  })
  useSeoMeta({
    title: 'ÉcouteSolidaire',
    ogTitle: 'ÉcouteSolidaire',
    description: 'This is ÉcouteSolidaire, let me tell you all about it.',
    ogDescription: 'This is ÉcouteSolidaire, let me tell you all about it.',
    ogImage: 'https://example.com/image.png',
    twitterCard: 'summary_large_image',
  })
</script>

