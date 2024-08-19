<script setup lang="ts">
import { RouterView } from 'vue-router';
</script>

<template>
  <div class="container-field">
    <RouterView />

    <div class="banner">
      <p>讓自然<br />點綴你的每一天</p>
    </div>
  </div>
</template>

<style scoped>
.banner {
  background-image: url('./assets/banner3.webp');
  background-position: 37% center;
  background-size: cover;
  padding-block: 396px;
}

.banner p {
  position: absolute;
  top: 28%;
  left: 5%;
  font-size: 7rem;
  color: #005c36;
  font-weight: 800;
}
</style>
