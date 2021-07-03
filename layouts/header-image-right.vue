<script setup lang="ts">
import { defineProps } from 'vue'

const props = defineProps<{
  header: string
  image: string
  imageClass?: string
  containerClass?: string
}>()
</script>

<template>
  <div flex="~ col">
    <h1 text="5xl">{{header}}</h1>
    <div flex="~ row 1" space="x-4" p="2" m="t-8" w="full" :class="containerClass">
      <div flex="1" text="xl">
        <slot />
      </div>
      <img w="80" self="center" :class="imageClass" :src="image"/>
    </div>
  </div>
</template>