<template>
  <div>
    <new-header2></new-header2>
    <new-body2></new-body2>
    <new-Footer2></new-Footer2>
  </div>
</template>

<script>
import NewHeader2 from "./components2/Header2";
import NewBody2 from "./components2/Body2.vue";
import NewFooter2 from "./components2/Footer2";

export default {
  name: "New",
  components: {
    NewHeader2,
    NewBody2,
    NewFooter2
  }
};
</script>

<style>
</style>
