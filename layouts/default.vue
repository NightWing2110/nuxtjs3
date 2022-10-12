<template>
  <div>
    <nav class="bg-purple-700 text-white">
      <NuxtLink to="/">Home</NuxtLink><br />
      <NuxtLink to="/about">About</NuxtLink><br />
      <NuxtLink to="/profile">Profile</NuxtLink>
    </nav>
    <slot></slot>
  </div>
</template>