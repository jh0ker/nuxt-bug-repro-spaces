<script setup lang="ts">
const pageName = 'foo bar'
</script>

<template>
  <div>
    <h1>Reproduction of static site generation bug</h1>

    <NuxtLink :to="`/bugged/${pageName}`">foo bar</NuxtLink>
    <br />
    <NuxtLink to="/bugged/test toast">test test</NuxtLink>
  </div>
</template>
