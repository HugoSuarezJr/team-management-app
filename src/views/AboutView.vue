<script setup>
import { useFlash } from '@/composables/useFlash';

let { flash } = useFlash();
</script>

<template>
<div>
  <p>
    <button @click="flash('About', 'It Works on the About Page!', 'error')">Click me</button>
  </p>
</div>
</template>