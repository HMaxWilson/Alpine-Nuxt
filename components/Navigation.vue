<template>
  <div class="hidden lg:flex">
    <DesktopNav :pages="pages" />
  </div>


  <div class="flex lg:hidden">
    <MobileNav :pages="pages" />
  </div>
</template>

<script setup>
const pages = [
  { name: "Home", path: "/" },
  { name: "Services", path: "/services" },
  { name: "Meet the Team", path: "/team" },
  { name: "Contact", path: "/contact" },
];
</script>