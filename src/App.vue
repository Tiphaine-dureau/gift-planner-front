<script setup lang="ts">
import { RouterView } from 'vue-router'
import ToolBar from './components/ToolBar.vue'
</script>

<template>
  <nav>
    <ToolBar />
  </nav>
  <main>
    <RouterView />
  </main>
</template>
