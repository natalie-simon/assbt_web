<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <!--C'est ici qu'il faudra mettre le bandeau -->
      <h1>Bienvenue sur la version 2 des bulleurs Toulonnais</h1>
    </div>
  </header>

  <RouterView />
</template>

<style scoped></style>
