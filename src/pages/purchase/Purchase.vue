<template>
  <div>
    <purchase-header3></purchase-header3>
    <purchase-body3></purchase-body3>
    <purchase-footer3></purchase-footer3>
  </div>
</template>

<script>
import PurchaseHeader3 from "./components3/Header3";
import PurchaseFooter3 from "./components3/Footer3";
import PurchaseBody3 from "./components3/Body3";

export default {
  name: "Purchase",
  components: {
    PurchaseHeader3,
    PurchaseFooter3,
    PurchaseBody3
  }
};
</script>

<style>
</style>
