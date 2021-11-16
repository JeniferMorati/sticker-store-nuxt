<template lang="html">
  <header class="p-2">
    <nav
      class="
        px-4
        justify-between
        w-full
        rounded-full
        bg-white
        flex
        shadow-lg
        border-gray-100 border
        items-center
        justify-items-
      "
    >
      <NuxtLink class="flex center items-center justify-items-center" to="/">
        <img src="../assets/logo.png" alt="Logo do site" />
        <h1 class="text-xl font-bold">Sticker Store</h1>
      </NuxtLink>
      <ul class="flex space-x-4 items-center justify-items-center">
        <li>
          <NuxtLink to="/produtos">Produtos</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/produtos">Carrinho</NuxtLink>
        </li>
        <li>
          <LoginButton />
        </li>
        <li>
          <RegisterButton />
        </li>
      </ul>
    </nav>
  </header>
</template>
<script>
export default {}
</script>
<style lang=""></style>
