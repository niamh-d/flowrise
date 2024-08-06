<script setup lang="ts">
const settings = useSettings();
</script>

<template>
  <Bounded as="header">
    <Logo />
    {{ settings }}
  </Bounded>
</template>
