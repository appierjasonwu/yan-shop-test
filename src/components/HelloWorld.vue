<template>
  <div style="text-align:center">
    Welcome to yanshop
  </div>
  <div class="hello">
    <div class="menu">
      <div class = "menu-item">
        <h1>Home</h1>
      </div>
      <div class = "menu-item">
        <h1>Login</h1>
      </div>
      <div class = "menu-item">
        <h1>Cart</h1>
      </div>
    </div>
    <br>
    <div class="menu">
      <div class = "menu-item">
        <h1>Clothes</h1>
      </div>
      <div class = "menu-item">
        <h1>Pants</h1>
      </div>
    </div>
    
    <div class = "name">
      <div class = "pants">
        <div>1.Brown pants</div>
        <img  src = "../assets/img/Brownpants.jpg" height="250" width="250" style ="margin-right: 100px;">
        <div>price:500</div>
      </div>
      <div class = "pants">
        <div>2.Green pants</div>
        <img  src = "../assets/img/Greenpants.jpg" height="250" width="250" style ="margin-right: 100px;">
        <div>price:1300</div>
      </div>
      <div class = "pants">
        <div>3.Gray pants</div>
        <img  src = "../assets/img/Graypants.jpg" height="250" width="250" >
        <div>price:1000</div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.name{
  display:flex;
  align-items: center;
  vertical-align: middle;
  width: 100vw;
  height:100vh;
}
.letter{
  margin:10;
}
.menu {
  display: flex;
  align-items: center;
  justify-content: space-around;
}
.menu-item{
  flex:1;
  border:3px solid rgb(47, 167, 231);
  text-align: center;
  font-size: 20px;
}
</style>
