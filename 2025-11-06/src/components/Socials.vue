<script lang="ts" setup>
defineProps<{
  click?: number
}>()
</script>

<template>
  <div class="text-xs flex-row flex justify-center gap-8">
    <span v-click="click" class="flex flex-row gap-1 op-60 items-center forward:delay-50 backward:delay-200">
      <span class="size-4 inline-block i-simple-icons-linkedin" />
      <a href="https://www.linkedin.com/in/klaygomes" target="_blank">klaygomes</a>
    </span>
    <span v-after class="flex flex-row items-center gap-1 op-60 forward:delay-100 backward:delay-150">
      <span class="size-4 inline-block i-simple-icons-github" />
      <a href="https://github.com/klaygomes" target="_blank">klaygomes</a>
    </span>
    <span v-after class="flex flex-row items-center gap-1 op-60 forward:delay-150 backward:delay-100">
      <span class="size-4 inline-block i-simple-icons-x" />
      <a href="https://x.com/klaygomes" target="_blank">@klaygomes</a>
    </span>
    <span v-after class="flex flex-row items-center gap-1 op-60 forward:delay-200 backward:delay-50">
      <span class="size-4 inline-block i-simple-icons-stackoverflow" />
      <a href="https://stackoverflow.com/users/136258/cleiton" target="_blank">klaygomes</a>
    </span>
  </div>
</template>
