<script setup lang="tsx">
import { useRouter } from 'vue-router'
const router = useRouter()

const text = 123
</script>

<template>
  <div>{{ text }}</div>
  <div @click="router.push('/login')">login</div>
</template>

<router>


</router>
