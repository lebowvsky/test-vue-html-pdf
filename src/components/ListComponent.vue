<template>
  <h2>ListComponent</h2>
  <ListItemCoponent v-for="item in nbr" :key="item" />
</template>

<script lang="ts" setup>
import ListItemCoponent from "./ListItemCoponent.vue";
const nbr = [1, 2, 3, 4, 5, 6, 7, 8];
</script>
