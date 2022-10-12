<template>
  <div>
    <button @click="moveToAbout">Take me to About Page</button>
    Alazul
  </div>
</template>

<script setup>
function moveToAbout() {
    navigateTo("about");
}
</script>