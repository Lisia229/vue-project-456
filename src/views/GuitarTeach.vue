<template lang="pug">
h1 教學內容
input(type="button" value="社團介紹" @click="goto('home')")
input(type="button" value="吉他社史" @click="goto('guitar')")
input(type="button" value="活動公告" @click="goto('guitar-events')")
</template>

<script setup>
import { useRouter } from 'vue-router'
const router = useRouter()
const goto = (name) => {
  // router.push({ name: name })
  router.push({ name })
}
</script>
