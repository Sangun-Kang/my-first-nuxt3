<script setup lang="ts">
const hello = "hello world!";
</script>
<template>
  <div>This is main Page {{ hello }}</div>
  <div>
    <nav>
      <ul>
        <li><NuxtLink to="/hoge">hoge</NuxtLink></li>
        <li><NuxtLink to="/moge">moge</NuxtLink></li>
      </ul>
    </nav>
  </div>
</template>
