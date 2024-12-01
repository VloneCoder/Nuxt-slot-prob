<template>
  <div>
    <h1>Debugging before slot</h1>
    <slot />
    <p>Debugging after slot</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  setup() {
    return {}
  },
})
</script>
