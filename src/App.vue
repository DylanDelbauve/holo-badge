<script setup>
import Badge from "./components/Badge.vue";
</script>

<template>
 <div>
   <Badge type="classic">Pro</Badge>
   <Badge type="bronze">Pro</Badge>
   <Badge type="silver">Pro</Badge>
   <Badge type="gold">Pro</Badge>
   <Badge type="platinum">Pro</Badge>
   <Badge type="diamond">Pro</Badge>
   <Badge type="funk-1">Pro</Badge>
 </div>
</template>

<style scoped>
div {
  display: flex;
  gap: 15px;
}
</style>
