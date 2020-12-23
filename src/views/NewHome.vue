<template lang ="pug">
  .back0
    .backgradient
      .mount
      .mount2
          
</template>

<script>
export default {
  name: "NewHome"
}
</script>

<style scoped>
  .back0{
    background-color: lightgray;
    position: absolute;
    width: 90vw;
    height: 100vh;
    margin-top: 5vh;
    margin-left: 5vw;
  }
  .backgradient{
  
    background-color: darkgray;
    background: linear-gradient(0deg, rgba(50,50,50,1) 0%, rgba(125,125,125,1) 35%, rgba(200,200,200,1) 100%);
    width: 80vw;
    height: 90vh;
    margin-top: 5vh;
    margin-left: 5vw;
    border-color: black;
    border: 5px solid black;
    position: absolute;
    overflow: hidden;
    
  }
  .mount{
    position: absolute;
    background-image: url("../assets/mount1.png");
    width: 90vw;
    height: 90vh;
    background-repeat: no-repeat;
    
  }
  .mount2{
    position: absolute;
    background-image: url("../assets/mount2.png");
    width:  90vw;
    height: 90vh;
    background-repeat: no-repeat;
    margin-top: 15vh;

    
  }
</style>