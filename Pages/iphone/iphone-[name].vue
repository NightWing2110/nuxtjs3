<template>
  <div>
    <Head>
      <Title>
        Nuxt3 - Iphone {{ name }}
      </Title>
    </Head>
    <p>Iphone {{ name }}</p>
  </div>
</template>
>

<script setup>
const route = useRoute();

const name = computed(() => {
  return route.params.name.replaceAll("-", " ");
});

// useHead({
//   title: `Nuxt3- Iphone ${route.params.name}`,
// })
</script>
