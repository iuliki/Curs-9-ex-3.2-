<template>
  <div class="container">
    <div class="row">
      <div class="col">
        <h1 class="justify-content-center d-flex">Home</h1>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <button @click="countUp" class="btn btn-warning">
          count: {{ count }}
        </button>
      </div>
    </div>
  </div>
</template>
<script setup>
import { ref } from 'vue';
import { useRouter } from 'vue-router';
const router = useRouter();
const count = ref(0);
function countUp() {
  if (count.value < 4) count.value++;
  else {
    count.value = 0;
    router.push('/about');
  }
}
</script>
