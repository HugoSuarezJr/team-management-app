<script setup>
// import { ref, watch } from 'vue';
import { useStorage } from '@/composables/useStorage';

let food = useStorage('food', 'salad');

</script>

<template>
<main>
  <p>
    What is your favorite food <input type="text" v-model="food" />
  </p>

</main>
</template>
