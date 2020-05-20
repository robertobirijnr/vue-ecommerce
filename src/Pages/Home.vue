<template>
  <div>
    <Navbar></Navbar>
    <Jumbo></Jumbo>
    <NewArrivals></NewArrivals>
    <Footer></Footer>
  </div>
</template>

<script>
import Navbar from "../components/Navbar";
import Jumbo from "../components/jumboImage";
import NewArrivals from "../components/NewArrivals";
import Footer from "../components/Footer";
export default {
  name: "Vue-Ecommerce",
  components: {
    Navbar,
    Jumbo,
    NewArrivals,
    Footer
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
body {
  font-family: "Montserrat";
}
</style>
