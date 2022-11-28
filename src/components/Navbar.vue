<template>
  <nav class="navbar navbar-light bg-light justify-content-beetween">
    <div>
      <img src="../assets/logo1.png" alt="" />
    </div>
    <div class="d-flex">
      <a class="nav-link text-dark" href="#"><b>Showcase</b></a>
      <a class="nav-link text-dark" href="#"><b>Catalog</b></a>
      <a class="nav-link text-dark" href="#"><b>Delivery</b></a>
      <a class="nav-link text-dark" href="#"><b>Rewards</b></a>
      <a> <img src="../assets/cart.png" width="30px" height="30px" /></a>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavbarComponent",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
