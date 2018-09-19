<template>
  <div>
  <Stock v-for="stock in stocks"></Stock>
  </div>
</template>

<script>
import Stock from './Stock.vue';
export default {
  data(){
    return{
      stocks:[
      {id:1,name:"BMW", price:110},
      {id:1,name:"Google", price:1110},
      {id:1,name:"Apple", price:2210},
      {id:1,name:"Tesla", price:10}
      ]
    }
  },
  components:{
    Stock
  }

}
</script>
