<template>
  <div
    class="
      bg-transparent
      fixed
      z-50
      w-screen
      h-screen
      top-0
      left-0
      flex
      justify-center
      items-center
    "
  >
    <div
      class="
        relative
        bg-white
        rounded
        shadow-lg
        z-50
        w-11/12
        xl:w-2/4
        h-3/5
        max-w-full max-h-full
      "
    >
      <button class="top-2.5 right-2.5 absolute">
        <img class="w-4 h-4" src="../assets/close.svg" />
      </button>
      <div class="p-4">
        <h1 class="text-xl pb-3">{{ title }}</h1>
        <div>
          <slot></slot>
        </div>
      </div>
    </div>
    <FadeShadow />
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
