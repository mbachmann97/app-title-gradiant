<script setup lang="ts">
</script>

<template>
  <main>
    <div class="wrap">
      <span>e<div class="spacer"></div>Prämie</span>
    </div>
  </main>
</template>

<style scoped>
.wrap {
  width: 20rem;
  display: flex;
  justify-content: center;
}

span {
  user-select: none;
  cursor: pointer;
  display: flex;
  justify-content: center;
  background: rgb(63,94,251);
  background: linear-gradient(90deg, rgba(63,94,251,1) 0%, rgba(252,70,107,1) 100%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 3rem;
  font-weight: bold;
}

.spacer {
  width: 1px;
}

span:hover .spacer {
  transform: rotate(-0.25turn);
  width: 5px;
  transition: all 0.2s ease;
}
</style>
