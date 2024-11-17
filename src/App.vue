<script setup>
 import Header from "./components/layouts/header/index.vue";
 import Footer from "./components/layouts/footer/index.vue";
 import Hero from "./components/pages/hero-page/index.vue";
 import Lessons from "./components/pages/lessons/index.vue";
 import Courses from "./components/pages/courses/index.vue";
 import Contact from "./components/pages/contact/index.vue"
</script>

<template>
<Header/>
<Hero/>
<section class="footer">
    <div class="container">
     <h2 >Bizning kurslarimiz kimga to’g’ri keladi ?</h2>
    </div>
    </section>
<Lessons/>
    <section class="footer">
    <div class="container">
     <h2 >PDP Junior  kurslari</h2>
    </div>
    </section>
<Courses/>
   <section class="footer">
    <div class="container">
     <h2 >Bog’lanish uchun</h2>
    </div>
    </section>
    <Contact/>
    <Footer/>
</template>
<style scoped lang="scss">
.footer{
  background-color: rgba(0, 181, 52, 1);
  padding: 20px;
  color: #fff;
  text-align: center;
  h2{

  }
}
</style>
