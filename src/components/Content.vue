<template>
  <div class="content">
    <p class="all_advantages">ALL ADVANTAGES</p>
    <div class="content_items">
      <div class="item">
        <img src="../assets/images/item.png" alt srcset />
        <p class="item_title">LLLLL LLLLL LLLLLLLLLLLL LLLLLLLLLL LLL.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
        <p>Lorem, ipsum dolor.</p>
        <p>Lorem ipsum dolor sit amet.</p>
      </div>
      <div class="item">
        <img src="../assets/images/item.png" alt srcset />
        <p class="item_title">LLLLL LLLLL LLLLLLLLLLLL LLLLLLLLLL LLL.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
        <p>Lorem, ipsum dolor.</p>
        <p>Lorem ipsum dolor sit amet.</p>
      </div>
      <div class="item">
        <img src="../assets/images/item.png" alt srcset />
        <p class="item_title">LLLLL LLLLL LLLLLLLLLLLL LLLLLLLLLL LLL.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
        <p>Lorem, ipsum dolor.</p>
        <p>Lorem ipsum dolor sit amet.</p>
      </div>
      <div class="item">
        <img src="../assets/images/item.png" alt srcset />
        <p class="item_title">LLLLL LLLLL LLLLLLLLLLLL LLLLLLLLLL LLL.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
        <p>Lorem, ipsum dolor.</p>
        <p>Lorem ipsum dolor sit amet.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Content"
};
</script>

<style scoped>
.content {
  color: #484e64;
}
.content .all_advantages {
  color: #484e64;
  font-weight: 100;
  text-align: center;
  letter-spacing: 0.4em;
  word-spacing: 0.5em;
  font-size: 1.27vw;
}

.content .content_items {
  display: flex;
  flex-direction: row;
  justify-content: center;
  /* max-width: 80vw; */
}

.content .content_items .item {
  display: flex;
  flex-direction: column;
  margin: 0 3vw;
  max-width: 17vw;
  /* min-width: 200px; */
}

.content .content_items .item img {
  width: 17vw;
}

.content .content_items .item p:not(.item_title) {
  font-size: calc(0.45vw + 0.75em);
}

.content .content_items .item .item_title {
  font-size: calc(0.55vw + 0.75em);
  font-weight: 500;
}
</style>