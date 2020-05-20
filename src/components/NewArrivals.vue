<template>
  <div class="new-arrival container">
    <div class="row">
      <div class="rol">
        <h3 class="title">New Arrivals</h3>
      </div>
    </div>
    <div class="row">
      <div
        v-for="product in productitem"
        v-bind:data="product"
        v-bind:key="product.name"
        class="item col-3"
      >
        <div class="card" style="width: 18rem;">
          <img :src="product.imgPath" class="card-img-top" width="300px" height="200px" alt="..." />
          <div class="card-body">
            <p class="product-name">{{product.name}}</p>
            <p class="price">{{product.price}}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      productitem: [
        {
          name: "Galaxy X5",
          price: "Ghs 8000.00",
          imgPath: require("@/assets/ipad-pro.jpg")
        },
        {
          name: "Ipad MaxS",
          price: "Ghs 8000.00",
          imgPath: require("@/assets/ipad-max.jpg")
        },
        {
          name: "Ipad MaxV",
          price: "Ghs 8000.00",
          imgPath: require("@/assets/earphone.jpg")
        },
        {
          name: "Laptop",
          price: "Ghs 8000.00",
          imgPath: require("@/assets/ipad.jpg")
        },
        {
          name: "Galaxy X5",
          price: "Ghs 8000.00",
          imgPath: require("@/assets/ipad-pro.jpg")
        },
        {
          name: "Ipad MaxS",
          price: "Ghs 8000.00",
          imgPath: require("@/assets/ipad-max.jpg")
        },
        {
          name: "Ipad MaxV",
          price: "Ghs 8000.00",
          imgPath: require("@/assets/earphone.jpg")
        },
        {
          name: "Laptop",
          price: "Ghs 8000.00",
          imgPath: require("@/assets/ipad.jpg")
        }
      ]
    };
  }
};
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