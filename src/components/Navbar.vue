<template>
  <div class="navbar z-10 w-full ">
    <nav class="mx-[40px] my-[48px] lg:mx-[140px]">
      <div class="flex justify-between ">
        <div class="logo flex before:bg-amber-500 before:w-[16px] before:h-[16px] before:ml-[70px]
        before:mt-[16px] before:absolute before:-z-10
        after:bg-amber-500 after:w-[16px] after:h-[16px] after:ml-[93px]
        after:mt-[16px] after:absolute after:-z-10">
          <img width="115px" src="../img/Jadoo.png">
        </div>
        <div class="2xl:hidden">
          <i class="fa-solid fa-align-justify"></i>
        </div>
        <div class="hidden 2xl:block text-sm">
          <ul class="flex">
          <li class="nav-li"><a href="">Desitnations</a></li>
          <li class="nav-li"><a href="">Hotels</a></li>
          <li class="nav-li"><a href="">Flights</a></li>
          <li class="nav-li"><a href="">Bookings</a></li>
          <li class="nav-li"><a href="">Login</a></li>
          <li class="nav-li border-[1px] border-gray-400 rounded-[10px]"><a href="">Sign up</a></li>
          <div>
            <li class="nav-li "><a href="">EN</a>
              <i class="fa-solid fa-angle-down ml-3"></i>
            </li>
          </div>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name:'Navbar',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>