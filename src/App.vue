<script setup>

import nombre from './components/Cabeza.vue'
import lado from './components/Cuerpo.vue'
</script>

<template >
  <header >
    <nombre class="text-2xl bg-blue-300 text-black-500" />
  </header >

  <main >
    <cabecera/>
  </main >
  <aside class="text-2xl bg-gray-300 text-black-500">
    <lado class="text-2xl bg-blue-300 text-black-500"/>
      
  </aside >
</template >
