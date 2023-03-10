<template>
  <button id="counter" @click="increment">{{ count }}</button>
</template>

<script setup>
import { ref, nextTick } from 'vue';
</script>
