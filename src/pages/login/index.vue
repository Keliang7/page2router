<script setup lang="tsx">
import { useRouter } from 'vue-router'
const router = useRouter()
const text = 'login'
</script>
<template>
  <div @click="router.push('/')">goback</div>
  <div>{{ text }}</div>
</template>
<style scoped></style>
