<script setup>

</script>

<template>
  <div id="workspace">
    <div style="display: flex; aling-items: center; background: #181818; width: 98%; padding: 1vh 0px; border-top-right-radius: 25px; padding-left: 2%">
      <div style="display: flex">
        <i class="fa-regular fa-file-code iconEA"></i>
        <p class="txM" style="color: #f9f9f9; padding-left: 15%; padding-top: 3px">index.js</p>
      </div>

      <div style="display: flex; padding: 0px 30px">
        <i class="fa-solid fa-file-pdf iconEA"></i>
        <p class="txM" style="color: #f9f9f9; padding-left: 10%; padding-top: 3px">README.pdf</p>
      </div>

      <div style="display: flex">
        <i class="fa-solid fa-file iconEA"></i>
        <p class="txM" style="color: #f9f9f9; padding-left: 10%; padding-top: 3px">.gitignore</p>
      </div>
    </div>
  </div>
</template>

<style scoped>

#workspace {
  width: 65%;
  height: 40vw;
  background: rgb(36, 33, 42);
  backdrop-filter: blur(5px);
  border-top-right-radius: 25px;
  border-bottom-right-radius: 25px;
}

.txM {
  font-size: 1.1vw;
}

.iconEA {
  font-size: 1vw;
  color: #f9f9f9;
  margin-block-start: 0px;
  margin-block-end: 0px;
  padding-top: 0.4vh;
}

@media (max-width: 756px) {
  .txM {
    color: #f9f9f9; font-size: 1.5vw; padding-left: 6%
  }
}

</style>