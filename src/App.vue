<script setup lang="ts">
import './app.css'
import { AddOption } from '@/logic.ts'
</script>

<template>
  <div class="canvas">
    <div id="circle" class="circle"></div>
    <form class="form" @submit="AddOption">
      <label for="text">Escribe la opción que quieras añadir a la ruleta</label>
      <input type="text" id="text" class="text" />
    </form>
  </div>
</template>
