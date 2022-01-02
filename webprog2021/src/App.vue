<template>
  <div class="app">
    <div :style="image" class="image">
      <section class="head">
        <div class="Logo">your daily <br> resource of facts</div>
        <div class="Daily">Random Fact of the day:</div>
        <div class="RFOTD">
          PLACEHOLDER: "Until 1994, world maps and globes sold in Albania only had Albania on them"
          </div>
      </section>
      </div>

<section class="RFGenerator">
  <div class="GeneratorText">random fact <br> generator</div>
    <div class="Generator">
      <div class="RandomFact"> PLACEHOLDER: "It has been estimated that humans use only 10% of 
    their brain."
    </div>
    </div>
    <button id="RandomButton" @click="loadapi">generate random fact</button>
</section>

    <section class="Category">
      <div class="CategoryItem1">random fact per category</div>
      <div class="CategoryItem2"> 
        <img src="https://i.redd.it/hcprm17ktpu21.jpg" alt="DogPicture" width="400px" height="400px">
        <button id="DogButton" @click="loadapi">generate dog fact</button>
      </div>
      <div class="CategoryItem3">
        <img src="https://img.welt.de/img/kmpkt/mobile172859821/6122500917-ci102l-w1024/Grumpy-Cat-Visits-The-Broadway-Cast-of-Cats.jpg" alt="CatPicture" width="400px" height="400px">
      <button id="CatButton" @click="loadapi">generate cat fact</button>
      </div>
      <div class="CategoryItem4">PLACEHOLDER: "Pekingese and Japanese Chins were so important in the ancient Far East that they had their own servants and were
                                    carried around trade routes as gifts for kings and emperors. Pekingese were even worshipped in the temples of China for centuries."
      </div>
      <div class="CategoryItem5">PLACEHOLDER: "Most cats are lactose intolerant, and milk can cause painful stomach cramps and diarrhea.
                                     It's best to forego the milk and just give your cat the standard: clean, cool drinking water."
      </div>
    </section>


      


   
  </div>
</template>





<script>
export default {
  name: 'App',
  components: {

  },

  data: () => ({
    image: { backgroundImage: "url(https://images.pexels.com/photos/1955134/pexels-photo-1955134.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260)" }

  }),

  methods: {
      loadapi() {      
      console.log("button clicked");
 
      }
    }
  

}

</script>

