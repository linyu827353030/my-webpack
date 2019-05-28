<template>
  <div>
    <register-header4></register-header4>
    <register-body4></register-body4>
    <hr>
    <br>
    <br>
    <register-footer4></register-footer4>
  </div>
</template>

<script>
import RegisterHeader4 from "./components4/Header4";
import RegisterBody4 from "./components4/Body4";
import RegisterFooter4 from "./components4/Footer4";

export default {
  name: "Register",
  components: {
    RegisterHeader4,
    RegisterBody4,
    RegisterFooter4
  }
};
</script>

<style>
</style>
