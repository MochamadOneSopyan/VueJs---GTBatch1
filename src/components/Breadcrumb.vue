<template>
  <div class="header">
    <a href="LuxSpace.html" class="text-dark">Home</a>
    <a>/</a>
    <a href="LuxSpace.html" class="text-dark">Office Room</a>
    <a>/</a>
    <a href="LuxSpace.html" class="text-dark">Details</a>
    <!-- <a>/</a> -->
    <!-- <a href="#" class=" text-dark"><b>Shipping</b></a> -->
  </div>
</template>

<script>
export default {
  name: "BreadcrumbComponent",
  props: {
    msg: String,
  },
};
</script>

<style>
.header {
  background-color: rgb(245, 244, 244);
  width: 100%;
  padding: 1em;
  border-width: 1px;
  text-align: start;
  margin-left: auto;
  /* height: auto; */
}
</style>
