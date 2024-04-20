<script setup>
import { ref } from 'vue'
import Logo from './Logo.vue'
import Button from './Buttonw.vue'
import Links from './Links.vue'

</script>

<template>
    <div class="mainT h">
      <Logo logo="Crocus" />
      <Links l1="Features" l2="About" l3="Blog" l4="Pricing" class="sizeH" />
      <Button msg="Sign In" class="sizeH" />
      <i class="fa-solid fa-bars iconS iconE"></i>
    </div>

    

    
</template>

<style scoped>

.h {
  height: 70px;
  width: 90%;
  justify-content: space-between;
  background-color: #141414;
  padding: 0 5%;
  border-bottom: 2px #222222 solid;
}

.iconS {
  display: none;
}

@media (max-width: 756px) { 
  .sizeH {
    display: none;
  }

  .iconS {
    display: block;
    font-size: 20px;
  }
}


</style>
