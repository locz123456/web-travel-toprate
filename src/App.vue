<template>
  <div class=" ">
    <Navbar/>
    <div class="absolute w-[700px] right-0 top-0 -z-10 hidden 2xl:block">
      <img class="m-0 p-0" src="./img/2.png">
    </div>
    <Introduce/>
    <Category/>
    <TopSelling/>
    <BookSteps/>
    <Testimonials/>
    <Produce/>
    <SubEmail/>
    <Footer/>
  </div>
</template>

<script>

import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";
import Introduce from "@/components/Introduce";
import Category from "@/components/Category";
import TopSelling from "@/components/TopSelling";
import BookSteps from "@/components/BookSteps";
import Testimonials from "@/components/Testimonials";
import Produce from "@/components/Produce";
import SubEmail from "@/components/SubEmail";
export default {
  name: 'App',
  components: {
    Footer,Navbar,Introduce,Category, TopSelling, BookSteps ,Testimonials, Produce, SubEmail
  }
}
</script>

<style>

</style>
