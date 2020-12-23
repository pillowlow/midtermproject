<template lang="pug">
    .parnet
        .test
            .maintitle
                h1 {{maintitle}}
        img( alt ="arrow" src='../assets/vvuetitle.png' width ="200" height ="100")
        .name-card-area(v-for='(item, index) in store')
            .blockstorename {{storename}}
              input(type='text'  v-model='item.name')
            .storeprice {{storeprice}}
              input(type='text'  v-model='item.price')
            .flaver {{storeflavor}}
              input(type='text'  v-model='item.flavor')
        .but
          button(v-on:click='addStore()') 增加v

        
</template>

<script>
      export default {
        
        data() {
          return {
            maintitle : "清大學餐推薦",
            storename : "店名",
            storeprice : "價格",
            storeflavor : "口味",
            addstore :{
              name : "",
              price : "",
              flavor : ""
            },
            store: [ 
              {
              name : "海盜滷味一號",
              price : "100",
              flavor : "asian"
              },
              {
              name : "海盜滷味二號",
              price : "200",
              flavor : "asian"
              },
            ]
          }
      },
    methods: {
      addStore(){
         this.store.push(this.addstore);   
      }
    }
  }
</script>

<style>
    .test{
        
        width: 200px;
        height: 40px;
        position: absolute;
        top: 20%;
        left: 50%;
        margin: -30px 0 0 -100px;
        
    }
    .maintitle{
        position: absolute;
        margin: -10px 0 0 35px;
        font-size: 10px;
        }
    .name-card-area {
      width: 200px;
      height: 100px;
      
        
       
      margin: 0 0 0 87vh;
      background-color: cadetblue;

    }
    
    
</style>
