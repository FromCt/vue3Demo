<script setup>
import { ref, onMounted } from "vue";

let count = ref(1);
function add() {
  console.log("add");
  count.value++;
}
</script>
<template>
  <div>
    this is count=={{ count }}

    <div><span @click="add">add</span></div>
  </div>
</template>
<style scoped></style>
