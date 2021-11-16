<template>
  <div
    class="
      relative
      bg-white
      rounded
      shadow-lg
      border
      border-gray-100
      w-max
      h-max
      max-w-full
      max-h-full
    "
  >
    <div class="p-4">
      <h1 class="text-xl pb-3">{{ title }}</h1>
      <div>
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: { type: String, required: false },
  },
}
</script>

<style></style>
