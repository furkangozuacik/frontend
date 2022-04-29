<template>
    <div>

      <div class="card grid gap-4 grid-cols-4 grid-rows-3" style="width: 20rem;">
  <img class="card-img-top" :src="cardsSection.image" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">{{cardsSection.header}}</h5>
    <p class="card-text">{{cardsSection.productDescription}} on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
        <!--<section id="features" class="section-area">
        <div class="features-top">
           

        </div>
        
        <div class="features-body">
            <div class="container">
                <div class="col3">
                    <div class="item">
                        <div class="zoom">
                            <img :src="cardsSection.image">
                            <!--<img :src="require(`@/img/${card.image$|||`)"> buradan geliyor sayfaya -->
                        <!--</div>
                        <div class="item-text">
                             <h1>{{cardsSection.header}}</h1>
                            <p> {{cardsSection.productDescription}}
                                Has there ever been a more iconic American car than the ’57 Chevy Bel Air? Of course there hasn’t, it’s not even close. Not even the Model T is as much a 
                                symbol of its age as the Bel Air. It represents American middle class postwar prosperity perfectly, and is a rare example of a car with styling that was exactly in line with contemporary design.</p>
                            <a href="#" class="btn-details">More Details</a>

                        </div>

                    </div>

                 </div>
            </div>
        </div>
    </section> -->
       

       <!-- <div><NewsCard v-for="card in cardsSection.cards"
        :key="card.id"
        :card="card" /> </div> -->

    </div>
    
</template>



<script>

export default {
   props: ['cardsSection']
}
</script>

<style scoped>


.item {
  padding: 10px 20px;
}

.zoom {
  position: relative;
  overflow: hidden;
  display: inline-block;
  width: 100%;
  vertical-align: top;
}

.zoom img {
  display: block;
  width: 100%;
  height: auto;
  transition: all 0.5s ease;
}

.item-text {
  text-align: center;
  padding: 5px;
  border: 2px solid #500d16;
}

.item:hover .zoom img {
  transform: scale(1.2);
}

.item:hover h3 {
  color: white;
}

.item:hover .item-text {
  background-color: #840909;
  color: white;
  transition: all 0.5s ease;
}
.btn-details {
  color: #840909;
  margin-bottom: 30px;
  padding: 5px 10px;
  text-decoration: none;
  border: 1px solid #840909;
  transition: all 0.5s ease;
}
.item:hover .btn-details {
  color: white;
  border: 1px solid white;
}

.item-text p {
  line-height: 1.3;
  margin: 20px 7px;
}

</style>