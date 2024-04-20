<script setup>

</script>

<template>
    <div id="files">
      <div style="display: flex; padding-top: 2vh; padding-left: 8%; align-items: center;">
        <i class="fa-solid fa-circle iconE" style="color: #ff4646"></i>
        <i class="fa-solid fa-circle iconE" style="color: #ffc143; padding-left: 4%"></i>
        <i class="fa-solid fa-circle iconE" style="color: #63ab3e; padding-left: 4%"></i>
        <p class="txM" style="color: #f9f9f9; padding-left: 6%; font-size: 1.2vw">Editor</p>
      </div>

      <div id="icons">
        <i class="fa-solid fa-folder iconE" style="color: #1fb2ce"></i>
        <i class="fa-solid fa-code-branch iconE"></i>
        <i class="fa-solid fa-magnifying-glass iconE"></i>
        <i class="fa-solid fa-layer-group iconE"></i>
        <i class="fa-solid fa-gear iconE"></i>
      </div>

      <div class="editRowF">
        <i class="fa-regular fa-folder iconE"></i>
        <p class="txM">wispy</p>
      </div>

      <div class="editRowF">
        <i class="fa-solid fa-chevron-right iconE"></i>
        <i class="fa-solid fa-folder iconE" style="padding-left: 6%"></i>
        <p class="txM">.github</p>
      </div>

      <div class="editRowF">
        <i class="fa-solid fa-chevron-right iconE"></i>
        <i class="fa-solid fa-folder iconE" style="padding-left: 6%"></i>
        <p class="txM">node_modules</p>
      </div>

      <div class="editRowF">
        <i class="fa-solid fa-chevron-down iconE"></i>
        <i class="fa-regular fa-folder iconE" style="padding-left: 6%"></i>
        <p class="txM">src</p>
      </div>

      <div class="editRowS">
        <i class="fa-solid fa-file iconE"></i>
        <p class="txM">.gitignore</p>
      </div>

      <div class="editRowS">
        <i class="fa-regular fa-file-code iconE"></i>
        <p class="txM">index.js</p>
      </div>

      <div class="editRowS">
        <i class="fa-solid fa-file-pdf iconE"></i>
        <p class="txM">README.pdf</p>
      </div>

    </div>
</template>

<style scoped>

#files {
  width: 15%;
  height: 40vw;
  background: rgba(77, 69, 89, 0.1);
  border-top-left-radius: 25px;
  border-bottom-left-radius: 25px;
}

.txM {
  color: #f9f9f9; font-size: 1vw; padding-left: 6%
}

.editRowF {
  display: flex; padding: 0 8.5%; align-items: center; padding-top: 8px
}

.editRowS {
  display: flex; padding: 0 21%; align-items: center; padding-top: 0.2vh
}

#icons {
  display: flex; padding: 20px 8%; align-items: center; justify-content: space-between
}

@media (max-width: 756px) {
  #icons {
    padding: 1vh 8%;
  }

  .editRowF {
    padding-top: 0.2vh;
  }

  .txM {
  color: #f9f9f9; font-size: 1.2vw; padding-left: 6%
  }
}

</style>