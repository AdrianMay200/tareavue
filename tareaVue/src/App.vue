<script setup>
//import HelloWorld from './components/HelloWorld.vue'
//import TheWelcome from './components/TheWelcome.vue'
///
import nombre from './components/cabecera.vue'
import lado from './components/lado.vue'
</script>

<template>
  <header>
    <nombre />
  </header>

  <main>
    <cabecera />
  </main>
  <aside class="bg-gray-200">
    <lado/>
      
  </aside>
</template>

