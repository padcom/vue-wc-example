<template>
  <div class="hello-world">
    <h1>Hello, world! {{ message }}</h1>
  </div>
</template>

<script lang="ts" setup>
const { message } = defineProps<{
  message: string,
}>()
</script>

<style lang="postcss">
h1 {
  font-size: 1.875rem;
  line-height: 2.25rem;
  background-color: var(--hello-clr, red);
}
</style>
