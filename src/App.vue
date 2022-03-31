<script setup>
import Assistant from "@/components/Assistant/Assistant.vue"
</script>

<template>
  <div class="center">
    <Assistant />
  </div>
</template>

<style lang="scss">
.center {
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  button {
    margin-top: 50px;
  }
}
</style>
