<template>
  <div class="middle">
    <div class="sisikursi">
      <img class="model1" src="../assets/side-1.png" alt="" />
      <img class="model2" src="../assets/side-2.png" alt="" />
      <img class="model3" src="../assets/side-3.png" alt="" />
      <img class="model4" src="../assets/side-1.png" alt="" />
      <img class="model5" src="../assets/side-2.png" alt="" />
    </div>

    <div class="image">
      <img
        alt="chair"
        id="utama"
        class="chair"
        style="height: 500px"
        src="../assets/kursiUtama.png"
      />
    </div>
    <br />

    <div class="word">
      <h2><b>Chair Thatty</b></h2>
      <h5>IDR 12.000.000</h5>
      <br />
      <a href="shipping.html">
        <button type="submit">
          <img src="../assets/cart.png" width="20px" height="20px" />
          <b>Add to Chart</b>
        </button></a
      >
      <br /><br />
      <b>About the product</b>
      <p>
        Tailored to a level of perfection synonymous with that<br />
        of a Savile Row suit and with understated quality in the<br />
        detail, Jetty has been influenced by timeless 1950s style.
      </p>
      <p>
        Providing a subtle nod to the past, Jetty also provides a perfect<br />
        solution for the way we work today. A comprehensive product family,
        Jetty features a variety of elegant chairs and shofas.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "GalleyComponent",
  props: {
    msg: String,
  },
};
</script>

<style>
.middle {
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.sisikursi {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  padding: 20px;
}

.word {
  width: 40%;
  padding: 30px;
}

.word button {
  width: 50%;
  height: auto;
  /* border: 1px solid; */
  border-radius: 30px;
  background-color: pink;
}
</style>
