<template>
  <div>
    <center>
      <div>
        <img src="../assets/logo1.png" alt="" />
      </div>
    </center>
    <br />
    <br />

    <div class="d-flex justify-content-around">
      <div>
        <b>Overview</b><br /><br />
        <p>Shipping</p>
        <p>Refund</p>
        <p>Promotion</p>
        <br />
      </div>

      <div>
        <b>Company</b><br /><br />
        <p>About</p>
        <p>Career</p>
        <p>Contact Us</p><br />
      </div>

      <div>
        <b>Explore</b> <br />
        <br />
        <p>Term & Condition</p>
        <p>Privacy Policy</p>
        <p>For Develover</p>
      </div>

      <div>
        <!-- <h5><b>Special Letter</b></h5> -->
        <b>Special Letter</b>
        <br />
        <form class="form-inline" id="form1">
          <input
            class="form-control mr-sm-2"
            id="inputNama"
            type="email"
            placeholder="Your Email Address"
            aria-label="email"
            required
          />

          <button
            class="rounded my-2 my-sm-0"
            type=" submit"
            style="background-color: pink"
            id="btnAlert"
          >
            <img src="../assets/tele-icon.png" alt="" width="30" />
          </button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterComponent",
  props: {
    msg: String,
  },
};
</script>

<style></style>
