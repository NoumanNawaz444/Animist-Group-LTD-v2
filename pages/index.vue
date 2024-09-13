<template>
  <main class="flex-1">
    <SectionsHeroSection />
    <SectionsSocialProuf />
    <SectionsLogoCloud />
    <SectionsServices />
    <SectionsAboutContent />
    <SectionsCta />
  </main>
</template>

<script lang="ts" setup>
useHead({
  title: 'Animist Group Limited',
  meta: [
    {
      name: 'Animist',
      content: "Animist Group LTD is a dynamic digital agency specializing in crafting visually stunning and engaging content. Our team of creative experts is passionate about pushing the boundaries of design and animation to help businesses stand out in today's competitive landscape.",
    },
  ],
  link:[
    {
        href:"https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;400;500;600;700&display=swap",
        rel:"stylesheet"
    }
  ],
})
</script>
