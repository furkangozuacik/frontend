<template>
        <!-- GALLERY SECTION-->
    <div>
        <section id="gallery" class="section-area">
        
            <div class="gallery-body">
                <div class="container">
                    <div class="gallery-slider">
                         <div class="gallery-slider-item">
                             <img src="@/img/a.png" >
                             <img src="@/img/b.png" >
                             <img src="@/img/c.png" >

                        </div>

                    </div>

                </div>

            </div>
        </section>
   
    </div>
    
</template>



<script>
export default {
  
    
}

</script>


<style scoped>

#contact-slider {
  height: 250px;
  background: url("../img/a.png") center center no-repeat;
  background-size: cover;
}

#contact-caption {
  height: 250px;
  background: rgba(0, 0, 0, 0.7);
}
#gallery {
  background-color: #d8d8d8a4;
}

#gallery-top {
  text-align: center;
}

.gallery-slider {
  overflow: hidden;
  width: 100%;
  margin-top: 20px;
  margin-left: 0px;
  margin-right: 100px;
}

.gallery-slider-item {
  width: 300%;
  position: relative;
  left: 0;
  animation: slide-animation 30s infinite;
}
.gallery-slider-item img {
  width: 33.33%;
  float: left;
  height: 550px;
}

@keyframes slide-animation {
  0% {
    left: 0;
  }
  25% {
    left: -100%;
  }
  50% {
    left: -200%;
  }
  75% {
    left: -100%;
  }
  100% {
    left: 0;
  }
}

</style>