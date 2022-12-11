<template>
  <div>
    Perfil de
    <!-- {{ $route.params }} -->
    {{ $route.params.name }}
  </div>
</template>
<script setup lang="ts">
defineProps<{name: string}>()
</script>
