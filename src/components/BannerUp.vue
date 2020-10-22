<template>
  <div class="banner_up">
    <p class="beyond_banking">BEYOND BANKING</p>
    <h1>
      Get control over
      your business
    </h1>
    <p class="nexcos_about">
      Nexoos PJ is the new banking platform that will allow
      you to operate your business seamlessly
    </p>
    <div class="get_in_line">
      <h5>Get in line</h5>
    </div>
  </div>
</template>

<script>
export default {
  name: "BannerUp"
};
</script>
<style scoped>
.banner_up {
  position: absolute;
  top: 16.8vw;
  left: 8.8vw;
  width: 40vw;
}

.banner_up .beyond_banking {
  font-weight: 100;
  margin-bottom: 0;
  letter-spacing: 0.25em;
  font-size: 0.88em;
}

.banner_up h1 {
  font-weight: 700;
  letter-spacing: 0.01em;
  word-spacing: 0.1em;
}

.banner_up .nexcos_about {
  color: #484e64;
  margin-top: 1.5vw;
}
.banner_up .get_in_line {
  position: absolute;
  top: calc(-1vw + 85.5%);
  left: calc(-6vw);
  width: 25vw;
  height: 280px;
  background-image: url(/img/nav_button.0429bcc6.png);
  background-size: 100% auto;
  background-repeat: no-repeat;
}

.banner_up .get_in_line h5 {
  /* position: absolute; */
  margin-top: calc(23.5% - 0.65vw);
  margin-left: calc(33% - 0.55vw);
  color: white;
  font-size: calc(2vw);
  font-weight: 700;
}
.banner_up .get_in_line:hover h5 {
  color: yellow;
}

@media only screen and (max-width: 630px) {
  .banner_up .get_in_line {
    position: static;
    background-position: -5.5vw -4.5vw;
    height: 2em;
  }
  .banner_up .get_in_line h5 {
    margin-left: calc(33% - 5.65vw);
    padding-top: 0.59vw;
    margin-top: 1em;
  }
}
</style>