<script lang="ts" setup>
defineProps<{
  as?: string;
}>();
</script>

<template>
  <Component :is="as || 'section'" class="px-4 py-10 md:px-6 md:py-14 lg:py-16">
    <slot />
  </Component>
</template>
