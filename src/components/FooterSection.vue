<template>
  <footer class="w-screen px-20 pt-16 md:pb-16 pb-0">
    <div
      class="flex flex-col md:h-full h-1/2 justify-between div1 pb-4 border-b-2 border-gray-400"
    >
      <h1 class="xl:text-4xl md:text-2xl text-xl mb-10 font-bold md:text-left">
        Your Company
      </h1>
      <p class="xl:text-xl md:text-lg mb-8 md:text-left">
        Halimun Street 25 <br />
        Jakarta, Indonesia <br />
        12850
      </p>
      <p class="xl:text-xl md:text-lg mb-0 md:text-left">www.yourdomain.com</p>
    </div>

    <div class="w-full h-full div2 pb-4 border-b-2 border-gray-400">
      <h1 class="text-lg md:text-left font-bold mb-2">Sitemap</h1>
      <ul class="pl-0 text-lg leading-8">
        <li class="mb-2">Home</li>
        <li class="mb-2">About</li>
        <li class="mb-2">Blog</li>
        <li class="mb-2">Menu</li>
        <li class="mb-2">Store</li>
        <li class="">Contact</li>
      </ul>
    </div>
    <div class="w-full h-full div3 pb-4 border-b-2 border-gray-400">
      <h1 class="text-lg md:text-left font-bold mb-2">Lorem Ipsum</h1>
      <ul class="pl-0 text-lg leading-8">
        <li class="mb-2">Neque</li>
        <li class="mb-2">Suspendisse</li>
        <li class="mb-2">Dictum</li>
        <li class="mb-2">Porttitor</li>
        <li class="mb-2">Tincidunt</li>
        <li class="">Enim Lobortis</li>
      </ul>
    </div>
    <div class="w-full h-full div4 pb-4 border-b-2 border-gray-400">
      <h1 class="text-lg md:text-left font-bold mb-2">Sit Amet</h1>
      <ul class="pl-0 text-lg leading-8">
        <li class="mb-2">Neque</li>
        <li class="mb-2">Suspendisse</li>
        <li class="mb-2">Dictum</li>
        <li class="mb-2">Porttitor</li>
        <li class="mb-2">Tincidunt</li>
        <li class="">Enim Lobortis</li>
      </ul>
    </div>
    <div class="w-full md:h-full h-1/2 flex flex-col md:text-left div5">
      <div class="flowerIcon mb-8"></div>
      <p class="text-lg mb-2 md:text-left">Copyright &copy; 2020 Freepik</p>
      <p class="text-lg mb-12 md:text-left">
        Company S.L. All rights reserved.
      </p>
      <div class="iconContianer">
        <v-icon class="bg-white p-1 mr-8 cursor-pointer" small color="#000"
          >mdi-facebook</v-icon
        >
        <v-icon class="bg-white p-1 mr-8 cursor-pointer" small color="#000"
          >mdi-instagram</v-icon
        >
        <v-icon class="bg-white p-1 cursor-pointer" small color="#000"
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
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  grid-template-rows: repeat(12, 1fr);
  background: #484f5b;
  min-height: 600px;
  color: #fff;
}
.flowerIcon {
  position: relative;
  right: 15px;
  width: 150px;
  height: 75px;
  background-image: url("@/assets/footerIcon.svg");
  background-repeat: no-repeat;
  background-position: left;
  background-size: contain;
}
.div1 {
  grid-area: 1 / 1 / 13 / 4;
}
.div2 {
  grid-area: 1 / 4 / 13 / 6;
}
.div3 {
  grid-area: 1 / 6 / 13 / 8;
}
.div4 {
  grid-area: 1 / 8 / 13 / 10;
}
.div5 {
  grid-area: 1 / 10 / 13 / 13;
}

@media (max-width: 1024px) {
  footer {
    grid-row-gap: 40px;
  }
  .div1 {
    grid-area: 7 / 1 / 13 / 7;
  }
  .div2 {
    grid-area: 1 / 1 / 7 / 5;
  }
  .div3 {
    grid-area: 1 / 5 / 7 / 9;
  }
  .div4 {
    grid-area: 1 / 9 / 7 / 13;
  }
  .div5 {
    grid-area: 7 / 7 / 13 / 13;
  }
}

@media (max-width: 768px) {
  footer ul {
    text-align: center;
  }

  .flowerIcon {
    width: 100%;
    height: 100%;
    right: 0;
    background-position: center center;
  }
  .iconContianer {
    margin: 0 auto;
  }
  .div1 {
    grid-area: 7 / 1 / 10 / 13;
  }
  .div2 {
    grid-area: 1 / 1 / 3 / 13;
  }
  .div3 {
    grid-area: 3 / 1 / 5 / 13;
  }
  .div4 {
    grid-area: 5 / 1 / 7 / 13;
  }
  .div5 {
    grid-area: 10 / 1 / 13 / 13;
  }
}

@media (min-width: 640px) {
  footer {
    min-height: 0;
  }
}
</style>
