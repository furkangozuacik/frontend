<template>
<div>
    
    <Navbar />
    
     <section id="cars-slider" class="slider">
        <div id="cars-caption" class="caption">
            <h1>Bilgi Kaynakları</h1>
            <p>just enjoy the ride classic car tour</p>

        </div>
     </section>

</div>
    
</template>

<script>
    export default {

    }
</script>

<style>
#cars-slider {
  height: 250px;
  background: url("@/img/kaynak.jpg") center center no-repeat;
  background-size: cover;
}

#cars-caption {
  height: 250px;
  background: rgba(0, 0, 0, 0.7);
}
h1 {
    padding-top: 50px;
    padding-bottom: 20px;
    color: white;
    text-align: center;
}
p {
    color: white;
    text-align: center;
}
</style>