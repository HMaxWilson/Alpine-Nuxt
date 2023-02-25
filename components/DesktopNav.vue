<template>
  <nuxt-link v-for="page in pages" :to="page.path" class="mx-2 my-auto font-light" :class="{ '!font-bold': $route.path === page.path }">{{ page.name }}</nuxt-link>
  <a href="https://alpinebuildingsolutions.co.uk" target="_blank" class="ml-2 w-[140px] text-center p-2 rounded-sm bg-white bg-opacity-25">
    <p>Looking for Alpine Building Solutions?</p>
  </a>
</template>

<script setup>
defineProps(["pages"]);
</script>