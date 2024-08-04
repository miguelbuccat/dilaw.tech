<script setup lang="ts">
useSeoMeta
  ({
    title
      : 'Dilaw.tech',
    ogTitle
      : 'Dilaw.tech',
    description
      : "Your partner in building your business's digital future",
    ogDescription
      : "Your partner in building your business's digital future",
    ogImage
      : 'https://dilaw.tech/dilaw.png',
    twitterCard
      : 'summary_large_image',
  })
</script>
<template>
  <div class="flex flex-col bg-black w-full min-h-screen justify-center items-center p-4 text-white gap-1">
    <img src="/primary-dark.png" width="400" />
    <span class="text-lg font-light">Your partner in building your digital future</span>
    <a href="mailto:contact@dilaw.tech"
      class="mt-4 transition duration-500 active:scale-75 bg-[#facc15] hover:bg-white text-xl text-black px-4 py-2 rounded-lg">Contact
      us</a>
  </div>
</template>