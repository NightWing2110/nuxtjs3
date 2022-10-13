<template>
  <div class="grid grid-cols-4 gap-4 mt-10">
    <nuxt-link to="/iphone/iphone-12" class="shadow-lg border rounded-lg text-center">
      <h1>Iphone12</h1>
      <div class="flex justify-center">
        <img width="100" src="/images/iphone12.jpg" alt="" />
      </div>
    </nuxt-link>
    <nuxt-link to="/iphone/iphone-12-mini" class="shadow-lg border rounded-lg text-center">
      <h1>Iphone12 Mini</h1>
      <div class="flex justify-center">
        <img width="100" src="/images/iphone12mini.jpg" alt="" />
      </div>
    </nuxt-link>
    <nuxt-link to="/iphone/iphone-11" class="shadow-lg border rounded-lg text-center">
      <h1>Iphone11</h1>
      <div class="flex justify-center">
        <img width="100" src="/images/iphone11.jpg" alt="" />
      </div>
    </nuxt-link>
    <nuxt-link to="/iphone/iphone-16" class="shadow-lg border rounded-lg text-center">
      <h1>Iphone-16</h1>
      <div class="flex justify-center">
        <img width="100" src="/images/iphone16.jpg" alt="" />
      </div>
    </nuxt-link>
  </div>
</template>

<script setup>
useHead({
  title: "Nuxt3-Iphone",
});
</script>
