<template>
  <div class="maame">
    <header>Login</header>
    <form>
      <div class="input-field">
        <input type="email" />
        <label>Email or Username</label>
      </div>
      <div class="input-field">
        <input type="password" />
        <label>Password</label>
      </div>
      <div class="button">
        <div class="inner"></div>
        <button>Login</button>
      </div>
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style scope>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #1da1f2;
  background-size: cover;
  background-position: center;
  text-align: center;
  font-family: "Montserrat";
}
.maame {
  position: relative;
  width: 400px;
  background: white;
  padding: 60px 40px;
}
header {
  font-size: 40px;
  margin-bottom: 60px;
}
.input-field,
form .button {
  margin: 25px 0;
  position: relative;
  height: 50px;
  width: 100%;
}
.input-field input {
  height: 100%;
  width: 100%;
  border: 1px solid silver;
  padding-left: 15px;
  outline: none;
  font-size: 19px;
}
input:focus {
  border: 1px solid #1da1f2;
}
.input-field label {
  position: absolute;
  top: 50%;
  left: 15px;
  transform: translateY(-50%);
  pointer-events: none;
  color: rgb(99, 93, 93);
  font-size: 18px;
}
input:focus ~ label {
  transform: translateY(-33);
  background: white;
  font-size: 16px;
  color: #1da1f2;
}
.button button {
  width: 100%;
  height: 50px;
  background: #1da1f2;
  color: aliceblue;
  border-radius: 15px;
}
</style>
