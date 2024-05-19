<script setup>

import QuizView from '@/components/Quiz/QuizView.vue';
</script>

<template>
<main>
  <QuizView :quiz="{ name: 'My first Quiz', questions: [] }"></QuizView>
</main>
</template>
