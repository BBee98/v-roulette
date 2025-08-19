<script setup lang="ts">
import './styles.css'
import type { RouletteProps } from './roulette.ts'

withDefaults(defineProps<RouletteProps>(), {
  options: () => ['Item 1', 'Item 2', 'Item 3'],
})
</script>

<template>
  <div class="circle">
    <div class="cheese"></div>
    <div class="cheese"></div>
    <div class="cheese"></div>
    <div class="cheese"></div>
  </div>
</template>
