<template>
  <div class="grid grid-cols-4 gap-4 mt-10">
    <nuxt-link to="/iphone/iphone-12" class="shadow-lg border rounded-lg text-center">
      <h1>Iphone12</h1>
      <div class="flex justify-center">
        <img width="100" src="/images/iphone12.jpg" alt="" />
      </div>
    </nuxt-link>
    <nuxt-link to="/iphone/iphone-12-mini" class="shadow-lg border rounded-lg text-center">
      <h1>Iphone12 Mni</h1>
      <div class="flex justify-center">
        <img width="100" src="/images/iphone12mini.jpg" alt="" />
      </div>
    </nuxt-link>
  </div>
</template>

<script setup>
useHead({
  title: "Nuxt3-Iphone",
});
</script>
