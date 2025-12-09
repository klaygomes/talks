<script lang="ts" setup>

</script>

<template>
  <div class="flex justify-center gap-8">
    <ToolCard v-click class="forward:delay-50 backward:delay-300" logo="i-logos-nodejs-icon" name="Node.js" />
    <ToolCard v-after class="forward:delay-100 backward:delay-250" logo="i-logos-react" name="React.JS" />
    <ToolCard v-after class="forward:delay-150 backward:delay-200" logo="i-logos-nextjs" name="Next.js" />
    <ToolCard v-after class="forward:delay-200 backward:delay-150" logo="i-logos-linux-tux" name="Linux" />
    <ToolCard v-after class="forward:delay-250 backward:delay-100" logo="i-logos-kubernetes" name="Kubernetes" />
  </div>
</template>
