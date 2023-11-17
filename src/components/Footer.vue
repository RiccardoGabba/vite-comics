<template>
      <div class="bg-dark p-3">
    <div class="container">
      <i class="fa-solid fa-arrow-right" style="color: #ffffff"> </i>
      <span class="display-2 text-white p-2">Content Goes Here</span>
      <i class="fa-solid fa-arrow-left" style="color: #ffffff"> </i>
    </div>
  </div>
  <div class="bg-primary p-4">
    <div class="container d-flex justify-content-between">
      <div>
        <img src="../images/buy-comics-digital-comics.png" alt="" />
        <span class="mx-2">Digital Comics</span>
      </div>
      <div>
        <img src="../images/buy-comics-merchandise.png" alt="" />
        <span class="mx-2">Digital Comics</span>
      </div>
      <div>
        <img src="../images/buy-comics-shop-locator.png" alt="" />
        <span class="mx-2">Digital Comics</span>
      </div>
      <div>
        <img src="../images/buy-comics-subscriptions.png" alt="" />
        <span class="mx-2">Digital Comics</span>
      </div>
      <div>
        <img src="../images/buy-dc-power-visa.svg" alt="" />
        <span class="mx-2">Digital Comics</span>
      </div>
    </div>
  </div>
  <div id="bg-dc" class="">
    <div id="bg-logo" class="container">
      <div class="text-white d-flex">
        <div class="p-3">
          <ul>
            <h2 class="text-center">DC COMICS</h2>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>

          <ul>
            <h2>SHOP</h2>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
        </div>
        <div class="p-3">
          <ul>
            <h2>DC</h2>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
        </div>
        <div class="p-3">
          <ul>
            <h2>DC</h2>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
        </div>
        <div></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
img {
  height: 72px;
  widows: 52px;
}

#bg-dc {
  background-image: url(../images/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
#bg-logo {
  background-image: url(../images/dc-logo-bg.png);
  background-position: right;
  background-repeat: no-repeat;
}
li {
  list-style-type: none;
}
</style>
