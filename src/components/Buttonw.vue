<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

</script>

<template>

    <btn class="btnW sign">
        <p>{{ msg }}</p>
    </btn>

    

    
</template>

<style scoped>

.sign {
    width: 120px;
    height: 45px;
    font-size: 1rem;
}

</style>
