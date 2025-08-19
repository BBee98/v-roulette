<script setup lang="ts">
import './app.css'
import RouletteForm from '@/components/Form/template.vue'
import Roulette from '@/components/Roulette/template.vue'
import { ref } from 'vue'

const options = ref([])

</script>

<template>
  <div class="canvas">
    <Roulette :options="options" />
    <RouletteForm />
  </div>
</template>
