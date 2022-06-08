<template>
  <div class="mt-[150px] lg:mx-[130px] mx-[50px] mb-44 flex center">

    <div class="center lg:w-[1170px] w-[460px] lg:h-[407px] h-[280px] bg-[#EFEAFF] rounded-tl-[130px] rounded-b-2xl py-[74px] text-[33px] font-semibold">
      <div class="float-right relative mt-[-100px] mr-[50px]">
        <div class="w-[70px] h-[70px] bg-[#747DEF] items-center justify-center flex rounded-full absolute mb-80 ">
          <i class="fa-solid fa-location-arrow text-white text-[34px]"></i>
        </div>
      </div>
      <div class="center">
        <h1 class="text-[#5E6282] lg:text-[33px] text-[18px]">
          Subscribe to get information, latest news and other <br>
          interesting offers about Cobham
        </h1>
        <div class="flex center mt-16">
          <div class="lg:w-[420px] lg:h-[68px] w-[200px] h-[40px] flex rounded-xl bg-white">
            <i class="fa-solid fa-envelope text-gray-500 text-lg lg:mt-5 mt-2 ml-5 "></i>
            <input type="email" placeholder="Your email" class="px-5 py-2 w-[350px] text-sm outline-none rounded-xl">
          </div>
          <button class="lg:w-[180px] lg:h-[68px] h-[40px] w-[70px] bg-[#FF8E6C] ml-10 lg:ml-5 text-white rounded-xl">
            <p class="lg:text-[17px] text-[14px]">Subscribe</p>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SubEmail',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
