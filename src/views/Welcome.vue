<script setup lang="ts">
import { Sticker } from "lucide-vue-next";
</script>

<template>
  <div data-with-fallback="emtpy">
    <div />
    <div data-when="empty">
      <Sticker />
      <p>Welcome!</p>
    </div>
  </div>
</template>
