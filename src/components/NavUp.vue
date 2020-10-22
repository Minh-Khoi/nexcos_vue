<template>
  <div class="nav_up">
    <div class="logo">
      <img src="../assets/images/nexcos_logo.png" alt />
    </div>
    <div class="nav_button">
      <h5>Get in line</h5>
    </div>

    <BannerUp />
    <img src="../assets/images/banner1.png" class="mobile_hidden" alt srcset />

    <banner-down />
    <img src="../assets/images/banner2.png" class="mobile_hidden" alt srcset />
  </div>
</template>

<script>
import BannerUp from "../components/BannerUp.vue";
import BannerDown from "../components/BannerDown.vue";

export default {
  name: "navup",
  components: {
    BannerUp,
    BannerDown
  }
};
</script>

<style scoped>
.nav_up {
  /* position: absolute; */
  /* top: 0; */
  /* left: 0; */
  background-image: url("../assets/images/bannerUP.png");
  background-size: 100% auto;
  width: 100vw;
  min-height: calc(100vw * 1.25 + 7vw);
}

.logo img {
  width: 29.4vw;
}

.nav_button {
  position: absolute;
  top: -1vw;
  right: 0;
  width: 25vw;
  height: 280px;
  background-image: url("../assets/images/nav_button.png");
  background-size: 100% auto;
  background-repeat: no-repeat;
}
.nav_button h5 {
  /* position: absolute; */
  margin-top: calc(23.5% - 0.65vw);
  margin-left: calc(33% - 0.55vw);
  color: white;
  font-size: calc(2vw);
  font-weight: 700;
}

.nav_button:hover h5 {
  color: yellow;
}

.nav_up > img {
  display: none;
}

@media only screen and (max-width: 630px) {
  .nav_up {
    background-image: none;
  }
  .nav_up > *:not(.logo):not(.nav_button) {
    position: static;
    margin-left: 28vw;
    width: 50vw;
  }
  .nav_up > img {
    width: 60vw;
    margin-left: 20vw;
    display: block;
  }
}
</style>

