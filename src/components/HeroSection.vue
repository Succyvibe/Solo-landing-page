<template>
  <div class="hero-bg h-full bg-[#22195b] relative cover z-10 p-5 md:p-16">
    <div
      class="container mx-auto px-4 md:px-0 md:flex text-white justify-between items-center"
    >
      <div class="md:w-[40%]">
        <h1 class="text-4xl md:text-4xl lg:tex-6xl xl:text-7xl font-bold mb-3">
          Welcome to Solo Code
        </h1>
        <p class="text-md md:text-lg">
          Learn advanced programming concept without the hassle of
        </p>
        <button
          class="bg-white w-full lg:w-[50%] text-blue-900 py-2 px-6 mt-10 text-xl font-semibold rounded-xl hover:bg-[#22195b] transition duration-300 ease-in hover:text-white border"
        >
          Get Started
        </button>
      </div>
      <div
        class="md:w-[50%] lg:w-[30%] border rounded-xl bg-white shadow-2xl mt-4 md:mt-0"
      >
        <form class="p-4 md:p-8">
          <p class="text-blue-900 mb-3">Sign Up here</p>
          <div class="grid grid-cols-3 gap-4 mb-5 md:mb-2 w-full">
            <div
              class="flex justify-center border hover:bg-blue-900 transition durarion-300 ease-in rounded-md shadow-md py-2 px-8 md:py-2 lg md:px-6"
            >
              <img src="../assets/imgs/LinkedIN_black.png" alt="Linked-logo" />
            </div>
            <div
              class="flex justify-center border hover:bg-blue-900 transition durarion-300 ease-in rounded-md shadow-md py-2 px-8 md:py-2 lg md:px-6"
            >
              <img src="../assets/imgs/LinkedIN_black.png" alt="Linked-logo" />
            </div>
            <div
              class="flex justify-center border hover:bg-blue-900 transition durarion-300 ease-in rounded-md shadow-md py-2 px-8 md:py-2 lg md:px-6"
            >
              <img src="../assets/imgs/LinkedIN_black.png" alt="Linked-logo" />
            </div>
          </div>
          <div class="grid grid-cols-3 mb-4 md:mb-6">
            <div class="border-b"></div>
            <div class="text-center"><p class="text-black">or</p></div>
            <div class="border-b"></div>
          </div>

          <input
            class="w-full border-blue-900 border mb-4 md:mb-8 p-2 md:p-2 rounded-md"
            type="text"
            placeholder="Full Name"
          />

          <input
            class="w-full border-blue-900 border mb-4 md:mb-8 p-2 md:p-2 rounded-md"
            type="text"
            placeholder="Mobile number or email"
          />

          <input
            class="w-full border-blue-900 border mb-4 md:mb-8 p-2 md:p-2 rounded-md"
            type="password"
            placeholder="Password"
          />

          <button
            class="w-full bg-blue-900 rounded-md p-3 duration-300 transition md:p-2 hover:bg-blue-700"
          >
            Start
          </button>
        </form>
        <div class="border-t p-3 md:p-6 md:mt-1">
          <p class="text-gray-500 text-sm md:text-md">
            By signing up, you agree to our
            <a class="text-black" href="">Terms,</a
            ><a class="text-black" href="">Data Policy</a> and
            <a class="text-black" href="">Cookies</a>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeroSection",
  components: {},
};
</script>

<style>
.hero-bg::after {
  content: "";
  background: url(https://preview.colorlib.com/theme/parason/img/banner/xbanner-bg.png.pagespeed.ic.uBBpCtHGz9.png)
    left center no-repeat;
  background-size: cover;
  z-index: -1;
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>
