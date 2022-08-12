<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <main class="px-3">
    <header>
      <nav class="flex items-center justify-between">
        <h1 class="text-2xl font-mono">Signature</h1>
        <div class="flex space-x-6">
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/about">About</RouterLink>
        </div>
      </nav>
    </header>

    <RouterView class="mt-10" />
  </main>

</template>