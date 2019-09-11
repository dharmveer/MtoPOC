<template>
  <nb-container class="text-container">
    <nb-content>
          <text class="seperator">Signature Sandwiches</text>
      <nb-list-item avatar v-for="sandwich in listsandwiches">
        <nb-left>
            
        </nb-left>
        <nb-body>
          <nb-text>{{sandwich.name}}</nb-Text>
        </nb-body>
      </nb-list-item>
    </nb-content>
  </nb-container>
</template>
<style>
.seperator{
    background-color: yellow;
    color: black;
    font-size: 20px;
    text-align: center;
}
.text-container{
     margin-top: 25px;
}
</style>
<script>
export default {
  data: function() {
    return {
      listsandwiches: [
        {
            "id": 15003,
            "plu": 40804,
            "name": "Boar's Head Roast Beef",
            "regularPrice": 0,
            "lowCal": 470,
            "highCal": 650,
            "kioskImageFile": "0000040804_Roast_Beef_Half.png"
        },
        {
            "id": 15001,
            "plu": 40747,
            "name": "Boar's Head Blazing Buffalo",
            "regularPrice": 0,
            "lowCal": 450,
            "highCal": 630,
            "kioskImageFile": "0000040747_Blazing_Buffalo_Half.png"
        },
        {
            "id": 15049,
            "plu": 40745,
            "name": "Boar's Head Bold Grilled Cheese",
            "regularPrice": 0,
            "lowCal": 650,
            "highCal": 830,
            "kioskImageFile": "0000040745_Bold_Grilled_Cheese.png"
        },
        {
            "id": 15062,
            "plu": 40825,
            "name": "Avocado Toast w/ Bacon",
            "regularPrice": 3.49,
            "lowCal": 0,
            "highCal": 630,
            "kioskImageFile": "0000040825_Avocado_Toast_with_Bacon.png"
        },
        {
            "id": 15050,
            "plu": 40855,
            "name": "Chicken Tender Sub",
            "regularPrice": 0,
            "lowCal": 610,
            "highCal": 790,
            "kioskImageFile": "0000040855_Chicken_Tender_Half.png"
        },
        {
            "id": 15004,
            "plu": 40757,
            "name": "Boar's Head Farmhouse Ham",
            "regularPrice": 0,
            "lowCal": 290,
            "highCal": 470,
            "kioskImageFile": "0000040757_Farmhouse_Ham_Half.png"
        },
        {
            "id": 15040,
            "plu": 40754,
            "name": "Boar's Head Maple Honey Turkey",
            "regularPrice": 0,
            "lowCal": 350,
            "highCal": 900,
            "kioskImageFile": "0000040754_Maple_Honey_Turkey_Half.png"
        },
        {
            "id": 15000,
            "plu": 40813,
            "name": "Boar's Head Traditional Italian",
            "regularPrice": 0,
            "lowCal": 780,
            "highCal": 960,
            "kioskImageFile": "0000040813_Traditional_Italian_Half.png"
        },
        {
            "id": 15048,
            "plu": 40809,
            "name": "Boar's Head Ovengold Turkey Cranberry",
            "regularPrice": 0,
            "lowCal": 330,
            "highCal": 510,
            "kioskImageFile": "0000040809_Ovengold_Turkey_Cranberry_Half.png"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        },
        {
            "id": 15051,
            "plu": 18480,
            "name": "Rotisserie Chicken Salad",
            "regularPrice": 0,
            "lowCal": 480,
            "highCal": 640,
            "kioskImageFile": "0000018480_Rotisserie_Chicken_Salad.jpg"
        }
    ]
    };
  }
};
</script>