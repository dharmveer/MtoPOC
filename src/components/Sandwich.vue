<template>
  <nb-container class="text-container">
    <nb-content>
          <nb-h1 class="seperator">Signature Sandwiches</nb-h1>
          <nb-list-item avatar v-for="sandwich in listsandwiches">
        <nb-left>
        </nb-left>
        <nb-body>
          <nb-text>{{sandwich.name}}</nb-Text>
            <nb-text note :numberOfLines="1" v-for="sandwichItem in sandwich.item">{{sandwichItem.name}}</nb-Text>
        </nb-body>
      </nb-list-item>
    </nb-content>
  </nb-container>
</template>
<style>
.seperator{
    background-color: yellow;
    color: black;
    text-align: center;
}
.text-container{
     margin-top: 25px;
}
</style>
<script>
import axios from "axios";
  export default {
    data() {
      return {
        listsandwiches: []
      };
    },
    mounted() {
      axios({ method: "GET", "url": "http://10.101.252.29/MtoKiosk/mtoSandwich" }).then(result => {
        this.listsandwiches = result.data.item;
        //console.log(this.listsandwiches);
      }, error => {
        console.error(error);
      });
    }
  };
</script>