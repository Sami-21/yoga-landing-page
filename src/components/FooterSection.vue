<template>
  <footer
    class="w-screen grid grid-cols-12 grid-rows-1 px-36 pb-12 pt-16 md:pt-36"
  >
    <div class="flex flex-col text-left px-4 grid-cols-2">
      <h1 class="xl:text-4xl md:text-2xl text-xl mb-10 font-bold">
        Your Company
      </h1>
      <p class="xl:text-xl md:text-lg mb-8">
        Halimun Street 25 <br />
        Jakarta, Indonesia <br />
        12850
      </p>
      <p class="xl:text-xl md:text-lg mb-8">www.yourdomain.com</p>
    </div>

    <div class="w-full h-full flex">
      <div class="w-full h-full">
        <h1 class="text-xl font-bold mb-2">Sitemap</h1>
        <ul class="pl-0">
          <li class="text-xl mb-2">Home</li>
          <li class="text-xl mb-2">About</li>
          <li class="text-xl mb-2">Blog</li>
          <li class="text-xl mb-2">Menu</li>
          <li class="text-xl mb-2">Store</li>
          <li class="text-xl mb-2">Contact</li>
        </ul>
      </div>
      <div class="w-full h-full">
        <h1 class="text-xl font-bold mb-2">Lorem Ipsum</h1>
        <ul class="pl-0">
          <li class="text-xl mb-2">Neque</li>
          <li class="text-xl mb-2">Suspendisse</li>
          <li class="text-xl mb-2">Dictum</li>
          <li class="text-xl mb-2">Porttitor</li>
          <li class="text-xl mb-2">Tincidunt</li>
          <li class="text-xl mb-2">Enim Lobortis</li>
        </ul>
      </div>
      <div class="w-full h-full">
        <h1 class="text-xl font-bold mb-2">Sit Amet</h1>
        <ul class="pl-0">
          <li class="text-xl mb-2">Neque</li>
          <li class="text-xl mb-2">Suspendisse</li>
          <li class="text-xl mb-2">Dictum</li>
          <li class="text-xl mb-2">Porttitor</li>
          <li class="text-xl mb-2">Tincidunt</li>
          <li class="text-xl mb-2">Enim Lobortis</li>
        </ul>
      </div>
    </div>
    <div class="w-full h-full flex flex-col grid-cols-2">
      <div class="w-full h-32"></div>
      <p class="text-xl mb-2">Copyright &copy; 2020 Freepik</p>
      <p class="text-xl mb-2">Company S.L. All rights reserved.</p>
      <div class="iconContianer mt-4">
        <v-icon class="bg-white p-1 mr-8 cursor-pointer" small color="#000"
          >mdi-facebook</v-icon
        >
        <v-icon class="bg-white p-1 mr-8 cursor-pointer" small color="#000"
          >mdi-instagram</v-icon
        >
        <v-icon class="bg-white p-1 mr-8 cursor-pointer" small color="#000"
          >mdi-twitter</v-icon
        >
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style>
footer {
  grid-template-columns: (2fr, 3fr, 2fr);
  background: #484f5b;
  min-height: 600px;
  color: #fff;
}

footer div:nth-child(1) {
  grid-area: 1 / 1 / 2 / 4;
}
footer div:nth-child(2) {
  grid-area: 1 / 4 / 2 / 10;
}
footer div:nth-child(3) {
  grid-area: 1 / 10 / 2 / 13;
}

@media (min-width: 640px) {
  footer {
    min-height: 0;
  }
}
</style>
