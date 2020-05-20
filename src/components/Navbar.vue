<template>
  <div class="mynvabar container">
    <nav class="navbar navbar-expand-lg navbar-light">
      <a class="navbar-brand" href="#">
        <span class="o-color">Shoppye</span>
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">
              HOME
              <span class="sr-only">(current)</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">SHOP</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">MERCHANTS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">MY ACCOUNT</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>
<style  scoped>
.mynvabar .navbar-brand {
  font-weight: bold;
  font-size: 30px;
  color: #5c5c5c;
}

.mynvabar .navbar-nav {
  margin-top: 10px;
}

.mynvabar .navbar-nav li {
  padding-right: 20px;
}

.mynvabar .navbar-nav li a {
  color: #5c5c5c;
}
.o-color {
  color: #ffbb5d;
}
</style>