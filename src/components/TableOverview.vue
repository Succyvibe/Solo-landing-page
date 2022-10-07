<template>
  <section class="table-bg bg-[#22195b] relative h-full w-full cover z-10">
    <div class="container mx-auto">
      <div
        class="lg:w-[900px] xl:w-[1100px] mx-auto h-screen shadow-2xl pb-24 pt-10 text-center px-6"
      >
        <div class="md:flex justify-between">
          <div class="md:w-[60%] h-[400px] border rounded-xl bg-[#22195b]">
            <h2 class="text-2xl text-white font-semibold">Revenue Overview</h2>
          </div>
          <div
            class="md:w-[30%] border mt-4 md:mt-0 rounded-xl bg-[#22195b] h-[200px] md:h-[400px]"
          >
            <h2 class="text-2xl text-white font-semibold">Client Overview</h2>
          </div>
        </div>
        <div
          class="rounded-xl bg-[#22195b] mx-auto flex md:justify-center items-center px-10 md:px-10 pt-6 mt-3"
        >
          <table class="text-white w-full border border-white">
            <tr>
              <th class="border border-white p-3">Company</th>
              <th class="border border-white p-3">Contact</th>
              <th class="border border-white p-3">Country</th>
            </tr>
            <tr>
              <td class="border border-white p-3">Alfreds Futterkiste</td>
              <td class="border border-white p-3">Maria Anders</td>
              <td class="border border-white p-3">Germany</td>
            </tr>
            <tr>
              <td class="border border-white p-3">
                Centro comercial Moctezuma
              </td>
              <td class="border border-white p-3">Francisco Chang</td>
              <td class="border border-white p-3">Mexico</td>
            </tr>
          </table>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>
<style scoped>
.table-bg::after {
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
