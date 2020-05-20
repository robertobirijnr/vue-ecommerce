<template>
  <div>
    <Navbar></Navbar>
    <Jumbo></Jumbo>
  </div>
</template>

<script>
import Navbar from "../components/Navbar";
import Jumbo from "../components/jumboImage";
export default {
  name: "Vue-Ecommerce",
  components: {
    Navbar,
    Jumbo
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
body {
  font-family: "Montserrat";
}
</style>
