<template>
  <div>
    <nav class="bg-purple-700 shadow-lg p-3 text-white text_lg flex justify-between">
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about">About</NuxtLink>
      <NuxtLink to="/iphone">Iphone</NuxtLink>
      <NuxtLink to="/profile">Profile</NuxtLink>
    </nav>
    <slot></slot>
  </div>
</template>