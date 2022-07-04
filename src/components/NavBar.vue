<template>
  <nav
    class="w-screen md:h-40 h-28 z-50 flex justify-between items-center font-bold px-16 absolute top-0 left-0"
  >
    <img src="@/assets/flower.png" alt="flower" class="duration-300" />
    <ul
      id="NavItems"
      class="xl:w-8/12 lg:w-10/12 md:w-full md:flex md:h-full md:relative md:top-0 md:left-0 flex-col md:flex-row md:justify-between justify-evenly items-center xl:text-3xl lg:text-2xl text-xl font-light absolute fullTop left-0 text-center md:opacity-100 opacity-0 h-60 md:py-4 z-20 border-t-2 md:border-t-0 text-gray-600"
    >
      <li class="cursor-pointer">Home</li>
      <li class="cursor-pointer">About</li>
      <li class="cursor-pointer">Blog</li>
      <li class="cursor-pointer">Training</li>
      <li class="cursor-pointer">Event</li>
      <li class="cursor-pointer">Shop</li>
      <li class="cursor-pointer">Contact</li>
    </ul>

    <div @click="toggleMenu()" id="NavBarIcon" class="cursor-pointer md:hidden">
      <div class="bar1 h-1 w-9 bg-black my-2 duration-300"></div>
      <div class="bar2 h-1 w-9 bg-black my-2 duration-300"></div>
      <div class="bar3 h-1 w-9 bg-black my-2 duration-300"></div>
    </div>
  </nav>
</template>

<script>
export default {
  data: () => ({
    MenuClosed: true,
  }),
  methods: {
    toggleMenu() {
      document.querySelector("img").classList.toggle("opacity-0");
      document.querySelector("#NavItems").classList.toggle("fullTop");
      document.querySelector("#NavItems").classList.toggle("top-0");
      document.querySelector("#NavItems").classList.toggle("opacity-0");
      document.querySelector("#NavItems").classList.toggle("opacity-100");
      document.querySelector(".bar1").classList.toggle("bar1_translate");
      document.querySelector(".bar2").classList.toggle("opacity-0");
      document.querySelector(".bar3").classList.toggle("bar2_translate");
      this.menuClosed = !this.menuClosed;
    },
  },
};
</script>

<style scope>
#NavItems {
  /* width: 65vw; */
  list-style: none;
}

.bar1_translate {
  transform: rotate(-45deg) translate(-9px, 6px);
}
.bar2_translate {
  transform: rotate(45deg) translate(-9px, -9px);
}
@media (max-width: 768px) {
  #NavItems {
    display: flex;
    width: 100vw;
    height: 100vh;
    transition-duration: 500ms;
    z-index: -2;
    background-color: #fff;
  }
  .fullTop {
    top: -100vh;
  }
}
</style>
