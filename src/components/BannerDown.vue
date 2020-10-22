<template>
  <div class="banner_down">
    <p class="financial_freedom">FINANCIAL FREEDOM</p>
    <h4>
      Nexoos PJ is the new banking platform that will allow
      you to operate your business seamlessly
    </h4>
    <div class="ticked_list">
      <div class="row_of_list">
        <img src="../assets/images/ticked.png" alt="ticked" srcset />
        <span>Lorem ipsum dolor sit amet.</span>
      </div>
      <div class="row_of_list">
        <img src="../assets/images/ticked.png" alt="ticked" srcset />
        <span>Lorem ipsum dolor sit amet.</span>
      </div>
      <div class="row_of_list">
        <img src="../assets/images/ticked.png" alt="ticked" srcset />
        <span>Lorem ipsum dolor sit amet.</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BannerDown"
};
</script>

<style scoped>
.banner_down {
  position: absolute;
  width: 40vw;
  top: 72vw;
  right: 5vw;
}

.banner_down .financial_freedom {
  font-weight: 100;
  margin-bottom: 2.5vw;
  letter-spacing: 0.25em;
  font-size: 0.88em;
}

.banner_down h4 {
  color: #484e64;
  font-weight: 700;
}

.banner_down .ticked_list {
  display: flex;
  flex-direction: column;
  margin-left: -1vw;
}
.banner_down .ticked_list .row_of_list {
  display: flex;
  flex-direction: row;
}

.banner_down .ticked_list .row_of_list img {
  width: 3.6vw;
}
.banner_down .ticked_list .row_of_list span {
  padding-top: 0.4vw;
  padding-left: 0.5vw;
}
</style>