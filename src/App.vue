<template lang="pug">
  #app
    .head
    #nav
      router-link(to="/newhome") 首頁
      |  
      router-link(to="/about") 不要點
      |  
      router-link(to="/week10") 新竹美食
      |  
      router-link(to="/newhome") 還是首頁
      |  
    router-view
      
</template>

<style>
.head{
  position: fixed;
  width: 100vw;
  background-color: white;
  heigth:10vh;
  z-index: 9;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: right;
  color: #2c3e50;
  height: 10vh;
  background: url("./assets/paaper.png") rgba(100, 100, 100, 0.3);

}

#nav {
  padding: 10px;
  position: fixed;
  z-index: 10;
  background-color: white;
  background: url("./assets/paaper.png") rgba(255, 255, 255, 1);
  width: 100vw;
  border: 5px solid black;
  top: 0%;
  right: 0%;
  }
#nav:hover{
  box-shadow: 0px 5px 15px darkgrey;
}
#nav a {
  font-weight: bold;
  color: black;
  font-size:20px;
  
  margin-right: 5vw;
}

#nav a.router-link-exact-active {
  color: #534d3c;
}


</style>
