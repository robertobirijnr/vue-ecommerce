<template>
  <div class="new-arrival container">
    <div class="row">
      <div class="rol">
        <h3 class="title">New Arrivals</h3>
      </div>
    </div>
    <div class="row">
      <div class="item col-3">
        <img src="../assets/ipad-pro.jpg" width="300px" height="200px" alt />
        <p class="product-name">Goody Speaker</p>
        <p class="price">Ghs 2000.00</p>
      </div>
      <div class="item col-3">
        <img src="../assets/earphone.jpg" width="300px" height="200px" alt />
        <p class="product-name">Goody Speaker</p>
        <p class="price">Ghs 2000.00</p>
      </div>
      <div class="item col-3">
        <img src="../assets/ipad.jpg" width="300px" height="200px" alt />
        <p class="product-name">Goody Speaker</p>
        <p class="price">Ghs 2000.00</p>
      </div>
      <div class="item col-3">
        <img src="../assets/ipad-max.jpg" width="300px" height="200px" alt />
        <p class="product-name">Goody Speaker</p>
        <p class="price">Ghs 2000.00</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.new-arrival .title {
  color: #5c5c5c;
  margin-bottom: 40px;
}
.new-arrival .item .product-name {
  font-size: 18px;
  color: #5c5c5c;
  font-family: "Montserrat-Light";
  text-align: center;
  margin-top: 20px;
}

.new-arrival .item .price {
  font-size: 16px;
  color: #1abc9c;
  text-align: center;
  margin-top: -16px;
}
</style>