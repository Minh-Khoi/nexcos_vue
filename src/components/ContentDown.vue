<template>
  <div class="content_down">
    <p class="light_row">BEYOND BANKING</p>
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
  name: "ContentDown"
};
</script>

<style scoped>
.content_down {
  text-align: center;
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: calc(0.95em + 1.5vw);
}

.content_down * {
  max-width: 50vw;
}

.content_down .light_row {
  color: #484e64;
  font-weight: 100;
  text-align: center;
  letter-spacing: 0.4em;
  word-spacing: 0.5em;
  font-size: 1.27vw;
  margin-top: 12vw;
  margin-bottom: 5vw;
}

.content_down h1 {
  font-weight: 700;
  letter-spacing: 0.01em;
  word-spacing: 0.1em;
  margin-bottom: 1vw;
  font-size: calc(1em + 3vw);
}

.content_down .nexcos_about {
  color: #484e64;
  margin-top: 1.5vw;
}
.content_down .get_in_line {
  position: absolute;
  top: calc(2.5vw + 89.5%);
  left: calc(36.5vw);
  width: 25vw;
  height: 280px;
  background-image: url(/img/nav_button.0429bcc6.png);
  background-size: 100% auto;
  background-repeat: no-repeat;
}

.content_down .get_in_line h5 {
  /* position: absolute; */
  margin-top: calc(23.5% - 0.65vw);
  margin-left: calc(-0vw);
  color: white;
  font-size: calc(2vw);
  font-weight: 700;
}
.content_down .get_in_line:hover h5 {
  color: yellow;
}

@media only screen and (max-width: 630px) {
  .content_down .get_in_line {
    position: static;
    background-position: 0vw -4.5vw;
    height: 2em;
  }
  .content_down .get_in_line h5 {
    /* margin-left: calc(33% - 5.65vw); */
    /* padding-top: 0.59vw; */
    margin-top: 0.25em;
  }
}
</style>