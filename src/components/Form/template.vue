<script setup lang="ts">
import { AddOption } from './form.ts'
import { ref } from 'vue'
const optionText = ref('')
</script>

<template>
  <form class="form" @submit="AddOption(optionText)">
    <label for="text">Escribe la opción que quieras añadir a la ruleta</label>
    <input type="text" id="text" class="text" v-model="optionText"/>
  </form>
</template>

<style scoped>

</style>

