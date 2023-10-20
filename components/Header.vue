<template>
  <header class="w-full border-b border-slate-200 py-6">
    <div class="container">
      <div class="flex justify-between items-center">
        <div>
          <NuxtLink to="/" class="text-xl font-bold ml-12">DayStore</NuxtLink>
        </div>

        <nav class="flex items-center gap-6">
          <NuxtLink to="/" class="text-base">Home</NuxtLink>
          <NuxtLink to="/product" class="text-base">Products</NuxtLink>
          <NuxtLink to="/cart" class="text-base">Cart</NuxtLink>
          <NuxtLink to="/contact" class="text-base">Contact</NuxtLink>
        </nav>
      </div>
    </div>
  </header>
</template>