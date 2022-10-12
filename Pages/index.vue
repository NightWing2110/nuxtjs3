<template>
  <div>
    <NuxtLink to="/">Home</NuxtLink><br />
    <NuxtLink to="/about">About</NuxtLink>

    <button @click="moveToAbout">Take me to About Page</button>
    Alazul
  </div>
</template>

<script setup>
function moveToAbout() {
    navigateTo("about");
}
</script>