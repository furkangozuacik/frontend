<template>
    <div>
    <section id="features" class="section-area">
        <div class="features-top">
           

        </div>
        
        <div class="features-body">
            <div class="container">
                <div class="col3">
                    <div class="item">
                        <div class="zoom">
                            <img :src="card.imageUrl">
                        </div>
                        <div class="item-text">
                            <h5>{{card.header}}</h5>
                            <p> {{card.productDescription}}
                                Has there ever been a more iconic American car than the ’57 Chevy Bel Air? Of course there hasn’t, it’s not even close. Not even the Model T is as much a 
                                symbol of its age as the Bel Air. It represents American middle class postwar prosperity perfectly, and is a rare example of a car with styling that was exactly in line with contemporary design.</p>
                            <a href="#" class="btn-details">More Details</a>

                        </div>

                    </div>

                 </div>
            </div>
        </div>
    </section>
  </div>
    
</template>



<script>

export default {
    props:['card']
   
}
</script>

<style scoped>

</style>