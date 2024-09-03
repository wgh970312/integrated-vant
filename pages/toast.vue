<template>
  <div style="height: 100vh; background: #999;">
    <button @click="open">
      open
    </button>
  </div>
</template>

<script lang="ts" setup>
import { showToast } from 'vant'

function open() {
  showToast('Hello')
}
</script>

<style>

</style>