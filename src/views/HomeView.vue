<script setup>
import TabblableTextarea from "@/components/TabbableTextarea.vue";
import { ref } from "vue";

let comment = ref('test value');

setTimeout(() => {
  comment.value = "Changed up baby";
}, 2000);

</script>

<template>
<main>
  <form>
    <TabblableTextarea v-model="comment" style="width: 100%; height: 300px;" />
  </form>
</main>
</template>
