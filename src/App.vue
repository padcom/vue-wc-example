<template>
  <h1>I am in the main app</h1>
  <input v-model="message">
  <hello-world :message />
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const message = ref('from App.vue')
</script>
