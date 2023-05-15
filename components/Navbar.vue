<template>
  <nav
    class="fixed top-0 px-10 py-3 bg-white w-full flex justify-between items-center z-50 transition-all .5s ease"
  >
    <div class="text-black">
      <h1
        class="text-2xl font-semibold font-serif hover:text-red-500 transition-all ease"
      >
        Tutorgo
      </h1>
    </div>
    <ul class="md:flex hidden gap-3 font-serif">
      <li class="px-3 py-1 hover:bg-black hover:text-white transition-all ease">
        <a href="#">Beranda</a>
      </li>
      <li class="px-3 py-1 hover:bg-black hover:text-white transition-all ease">
        <a href="#about">Tentang</a>
      </li>
      <li class="px-3 py-1 hover:bg-black hover:text-white transition-all ease">
        <a href="#tutorial">Tutorial</a>
      </li>
    </ul>
    <div class="md:hidden text-2xl cursor-pointer">
      <span>🍔</span>
    </div>
  </nav>
</template>

<style>
html {
  scroll-behavior: smooth;
}
</style>
