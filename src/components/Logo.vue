<script setup>
import { ref } from 'vue'

defineProps({
  logo: String,
})

</script>

<template>
    <div class="mainT l">
      <i class="fa-solid fa-spa icon"></i>
      <h1>{{ logo }}</h1>
    </div>

    

    
</template>

<style scoped>

.l {
  width: 140px;
  color: #f9f9f9;
  font-size: 15px;
  vertical-align: middle;
  justify-content: space-between;
}

</style>