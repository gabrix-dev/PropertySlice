<template>
  <div class="font-sans antialiased" id="app">
    <nav class="flex items-center justify-between bg-orange-500 p-6">
      <div class="flex items-center flex-no-shrink text-white mr-6">
        <IconsHouse />
        <span class="font-semibold text-xl tracking-tight ml-3"
          >habitaclia</span
        >
      </div>
      <div class="flex w-1/5 space-x-5 text-white">
        <h2>Venta</h2>
        <h2>Casas</h2>
        <h2>Palamos</h2>
      </div>
      <SectionsIconsRow />
    </nav>
  </div>
</template>

<script setup>
function toggle() {}
</script>
