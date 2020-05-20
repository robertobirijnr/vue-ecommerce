<template>
  <div class="container featured-item">
    <div class="row">
      <div class="left col">
        <img src="../assets/AirPods.jpg" width="600px" height="300px" alt="Airpods" />
      </div>
      <div class="right col">
        <p class="title">Apple Earpod on demand</p>
        <div class="original-price">Ghs 7500.00</div>
        <div class="dic-price">Ghs 3700.00</div>
        <p id="buy">
          <a href="#" class="btn btn-primary" pull-right>BUY NOW</a>
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.featured-item {
  padding: 80px 0 80px 0;
}
.featured-item .right .title {
  font-size: 55px;
  font-family: "Montserrat-ExtraLight";
  color: #5c5c55;
  line-height: 1.3;
  margin-bottom: 30px;
}

.featured-item .right .original-price {
  color: #9b9b9b;
  font-size: 18px;
  padding-left: 15px;
  text-decoration: line-through;
  margin-top: -20px;
}
.featured-item .right .dic-price {
  color: #1abc9c;
  font-size: 28px;
  padding-left: 15px;
  font-family: "Montserrat-Medium";
  margin-top: -10px;
}
.featured-item .right .btn-primary {
  margin-top: 20px;
  color: white;
  background: #ffbb5d;
  border-radius: 100px;
  border: 0;
  padding: 8px 28px 8 28px;
}
#buy {
  padding-left: 25px;
}
</style>