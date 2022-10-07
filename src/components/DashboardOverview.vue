<template>
  <section class="dashboard-bg bg-[#22195b] relative cover z-10">
    <div class="container mx-auto xl:flex items-center justify-between pt-8">
      <div
        class="md:w-[50%] lg:w-[50%] xl:w-[30%] mx-auto rounded-xl bg-[#22195b] h-[300px] md:h-[400px] shadow-2xl pt-4 md:mt-0 text-center text-white px-6 border-t-2 lg:border-t-0"
      >
        <div class="mb-10">
          <p>1 out of 5</p>
          <h3 class="text-lg font-semibold">Title of movie</h3>
        </div>
        <p>Description</p>

        <div class="mx-auto mt-5 flex justify-between flex-col px-6 md:px-0">
          <input
            type="text"
            placeholder="Search"
            class="border p-2 rounded-md mb-3 md:mb-0"
          />
          <button
            class="border py-2 px-4 text-white hover:bg-white hover:text-[#22195b] transition duration-500 ease-in-out rounded-md text-lg font-semibold mt-3"
          >
            Submit
          </button>
        </div>
      </div>
      <div
        class="md:w-[768px] lg:w-[900px] h-full shadow-2xl pb-24 text-center mx-auto"
      >
        <div class="md:flex md:justify-center">
          <div class="">
            <div
              class="md:w-[700px] lg:w-[800px] h-[450px] rounded-xl bg-[#22195b] mt-20 overflow-x-auto flex md:justify-center items-center px-10 md:px-10"
            >
              <img
                class="md:w-[600px] h-[300px] md:h-[400px] cover rounded-md"
                src="../assets/imgs/Graph.png"
                alt=""
              />
              <img
                class="md:w-[600px] h-[300px] md:h-[400px] cover rounded-md ml-10"
                src="../assets/imgs/Graph.png"
                alt=""
              />
              <img
                class="md:w-[600px] h-[300px] md:h-[400px] cover rounded-md ml-10"
                src="../assets/imgs/Graph.png"
                alt=""
              />
            </div>
          </div>
        </div>
        <!-- <div class="md:flex md:justify-center">
          <div
            class="md:w-[700px] lg:w-[800px] h-[450px] rounded-xl bg-[#22195b] mt-20 overflow-x-auto flex justify-center items-center px-10 md:px-10"
          >
            <div class="md:w-[600px] h-[300px] md:h-[400px] cover rounded-md">
              <h3 class="text-white font-semibold">Text</h3>
              <p class="text-white">95%</p>
            </div>
          </div>
        </div> -->
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "DashboardOverview",
};
</script>

<style scoped>
.dashboard-bg::after {
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
