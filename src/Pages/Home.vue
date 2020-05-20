<template>
  <div>
    <Navbar></Navbar>
    <Jumbo></Jumbo>
    <NewArrivals></NewArrivals>
  </div>
</template>

<script>
import Navbar from "../components/Navbar";
import Jumbo from "../components/jumboImage";
import NewArrivals from "../components/NewArrivals";
export default {
  name: "Vue-Ecommerce",
  components: {
    Navbar,
    Jumbo,
    NewArrivals
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
body {
  font-family: "Montserrat";
}
</style>
