<script setup>
import { ref } from 'vue'

defineProps({
  l1: String,
  l2: String,
  l3: String,
  l4: String,
})

</script>

<template>
    <div class="links">
        <a href="" class="itemL">{{ l1 }}</a>
        <a href="" class="itemL">{{ l2 }}</a>
        <a href="" class="itemL">{{ l3 }}</a>
        <a href="" class="itemL">{{ l4 }}</a>
    </div>

    

    
</template>

<style scoped>

.itemL {
    text-decoration: none;
    color: #959595;
    transition-duration: 300ms;
    font-size: 1.2rem;
}

.itemL:hover {
    color: #555555;
}

</style>