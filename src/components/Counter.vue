<template>
  <div class="bg-gray-100 mb-4">
    <div>The count is: {{ count }}</div>
    <button class="border px-4 py-2 rounded" @click="count++">+1</button>
  </div>
</template>
<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
};
</script>