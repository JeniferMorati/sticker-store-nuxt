<template lang="html">
  <button class="bg-purple-700 text-white px-5 py-1 rounded-full">
    {{ title }}
  </button>
</template>
<script>
export default {
  props: {
    title: { type: String, required: false },
  },
}
</script>
<style></style>
