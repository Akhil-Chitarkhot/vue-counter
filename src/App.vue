<script setup>
import { ref } from 'vue'


const count = ref(0)

</script>

<template>
  <div class="flex items-center justify-center min-h-screen">
    <div class="card bg-neutral text-neutral-content w-80 h-80">
      <div class="card-body justify-center items-center">
        <div>
          <h2 class="card-title pb-4">Counter</h2>
          <p>Current Count : </p>
          <p class="pt-4"> {{ count }} </p>
        </div>
        <div class="card-actions pt-8">
          <button class="btn btn-success" @click = "count++">Add</button>
          <button class="btn btn-error" @click = "count--">Subtract</button>
        </div>
      </div>
    </div>
  </div>
  





</template>


