<template lang ="pug">
  .back0
    
    .backgradient
      .mount
      .mount2
      .leftlable
        .logo
          img( alt ="logo" src='../assets/logo-03.png' width ="200px" height ="200px" )
        .line(style ='width :20vw')
        .titleback(style = 'width :20vw; height: 150px'  )
          img(alt ="文化沙漠" src='../assets/160862528499538.png' width ="300px" height ="100px")
          img(alt ="補完計畫" src='../assets/160862605567855 (1)2.png' width ="100px" height ="30px"  )
    .recentnews
      .titleblocknews
        img(alt ="newimg" src='../assets/newstitle.png'  height ="40" style="margin: auto;margin-right: 10vw;width:10vw; margin-top:1vh")
      .line(style ='width :20vw;height :2px;margin-top: 8vh;margin-left: 5vw')
      .picture
        img(alt ="newimg" src='../assets/castle.jpg'  height ="95%" style="border: 2px solid black;width :20vw; margin-left=5vw;margin: auto")
      .newstext
          
</template>

<script>
export default {
  name: "NewHome"
}
</script>

<style scoped>
  .newstext{
    width: 20vw;
    height: 30vh;
    position: relative;
    float:left;
    margin-left: 5vw;
    margin-top: 1vh;
    background-color: lightgrey;
    border: 2px solid black;
  }
  .titleblocknews{
    width: 30vw;
    height: 50px;
    position: relative;
    float:left;
    background-color: lightgrey;
    background: url("../assets/paaper.png") rgba(100, 100, 100, 0.3);
  }
  .picture{
    width: 20vw;
    height: 30vh;
    position: relative;
    float:left;
    margin-left: 5vw;
    margin-top: 5vh;
    
    
  }
  .recentnews{
    width: 30vw;
    height: 80vh;
    background-color: white;
    border: 5px solid black;
    position: relative;
    z-index: 5;
    float:left;
    margin-left: 2vw;
    margin-top: 8vh;
    background: url("../assets/paaper.png") rgba(255, 255, 255, 1);
    
  }
  .recentnews:hover{

    box-shadow: 0px 5px 15px darkgrey;
  }
  .titleback{
    position: relative;
    margin-left: 10vh;
  }
  .logo{
    margin-top: 80px;
    margin-left: 27%;
    position: absolute;
  }
  .leftlable{
    width: 30vw;
    height: 70vh;
    position: relative;
    background-color: white;
    border: 3px solid black;
    margin-top: -20px;
    margin-left: 5vw;
    background: url("../assets/paaper.png") rgba(100, 100, 100, 0.3);
    
  }
  
  .leftlable:hover{
    
    box-shadow: 0px 5px 15px darkgrey;
  }
  .back0{
    background-color: lightgray;
    position: absolute;
    width: 100vw;
    height: 100vh;
    margin-top: 5vh;
    margin-left: 0vw;
    border: 5px solid black;
    background: url("../assets/tile.png") rgba(100, 100, 100, 0.3);
  }
  .backgradient{
  
    background-color: darkgray;
    background: linear-gradient(0deg, rgba(50,50,50,1) 0%, rgba(125,125,125,0.5) 35%, rgba(200,200,200,0) 100%);
    width: 60vw;
    height: 90vh;
    margin-top: 5vh;
    margin-left: 2vw;
    border: 5px solid black;
    position: relative;
    overflow: hidden;
    float:left;
    animation: bgmove1 30s infinite;
    -webkit-animation: bgmove1 30s linear infinite;
    
  }
  @keyframes bgmove1 {
    0%{
      background-color: black}
    50%{
      background-color: white
    }
    100%{
      background-color: black}
  }
  .backgradient:hover{

    box-shadow: 0px 5px 15px darkgrey;
  }
  .mount{
    position: absolute;
    background-image: url("../assets/mount1.png");
    width: 90vw;
    height: 90vh;
    background-repeat: no-repeat;
    float: left;
    
  }
  .mount2{
    position: absolute;
    background-image: url("../assets/mount2.png");
    width:  90vw;
    height: 90vh;
    background-repeat: no-repeat;
    margin-top: 15vh;
    float: left;
    
  }
  .line{
    postion: absolute;
    margin-top: 300px;
    margin-left: 10vh;
    height: 3px;
    background-color: black;
  }
</style>