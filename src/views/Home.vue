<template>
  <div class="home">
    <Navbar></Navbar>
    <About></About> 
    <Welcome></Welcome>
    <Benefits></Benefits>
    <Autism></Autism>
    <Contact></Contact>
    <Footer></Footer>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue"
import About from "@/components/About.vue"
import Welcome from "@/components/Welcome_abroad.vue"
import Benefits from "@/components/Benefits.vue"
import Autism from "@/components/Autism_center.vue"
import Contact from "@/components/Contact.vue"
import Footer from "@/components/Footer.vue"

export default {
  name: "Home",
  components: {
    Navbar,
    About,
    Welcome,
    Benefits,
    Autism,
    Contact,
    Footer
  },
};
</script>

<style lang="scss" scoped>
.home{
  width: 100%;
}
</style>