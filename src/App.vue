
<template>
  <div>Hola</div>
  <!-- 3. utilitzar el component al template -->
  <!-- <HelloWorld />
  <HelloWorld /> -->
  <Counter/>
</template>
<script>
// 1: importar el component
import HelloWorld from "./components/HelloWorld.vue";
import counter from "./components/Counter.vue";
export default {
  // 2: registrar el component
  components: {
    HelloWorld,
    Counter
  },
};
</script>
