<template>
  <div class="footer">
    <img src="../assets/images/footerIMG.png" alt srcset />
    <div class="social_items">
      <img src="../assets/images/footer_items/facebook.png" alt="facebook" />
      <img src="../assets/images/footer_items/linkedin.png" alt="linkedin" />
      <img src="../assets/images/footer_items/instagram.png" alt="instagram" />
      <img src="../assets/images/footer_items/twitter.png" alt="twitter" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style scoped>
.footer {
  /* background-image: url('../assets/images/footerIMG.png'); */
  position: relative;
  top: 15.9vw;
}

.footer img {
  width: 100vw;
}

.footer .social_items {
  position: absolute;
  display: flex;
  flex-direction: row;
  top: 8vw;
  right: 0;
}

.footer .social_items img {
  width: 1.7vw;
  margin-right: 2.8vw;
}
.footer .social_items img:hover {
  transform: scale(1.5);
}
</style>