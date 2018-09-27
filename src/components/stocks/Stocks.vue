<template>
  <div>
  <Stock v-for="stock in stocks" :stock="stock"></Stock>
  </div>
</template>

<script>
import Stock from './Stock.vue';
export default {
  data(){
    return{
      stocks:[
      {id:1,name:"BMW", price:110},
      {id:2,name:"Google", price:1110},
      {id:3,name:"Apple", price:2210},
      {id:4,name:"Tesla", price:10}
      ]
    }
  },
  components:{
    Stock
  }

}
</script>
