<template>
<div>
    
    <div class="pb-5"><Navbar /></div>
    
    
     <section id="cars-slider" class="slider">
        <div id="cars-caption" class="caption">
            <h1>Muhendislik Laboratuvarı</h1>
            <p>Üniversitemiz öğrencileri okulumuzun son teknolojiyle donatılmış laboratuvarlarından faydalanabilirler. </p>

        </div>
     </section>
     <div class="row pt-5">
        <div class="col-lg-8 mx-auto">
            <!-- List group-->
            <ul class="list-group shadow">
                <!-- list group item-->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">OPTIKA SFX-91D Entegre Kameralı Dijital Binoküler Stereomikroskop
</h5>
                            <p class="font-italic text-muted mb-0 small">OPTIKA MS/SFX serisi stereo mikroskoplar, hem eğitim hem de amatör kullanıcıların her türlü ihtiyacını karşılamak için tasarlanmıştır. Ergonomik dizaynı ile kullanım kolaylığı ve yüksek kalite akromatik optik bileşenleri ile net stereoskopik görüntüler elde edilir.</p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/mikro.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item-->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Creality 3D Crealıty Ender 3 V2 3D Yazıc</h5>
                            <p class="font-italic text-muted mb-0 small"> 3D yazıcı yenilikçi yapısı ile tüm kullanıcı tiplerine hitap eden bir tasarım geliştirmiştir. Kullanışlı arayüzü ile 3D baskı işlemleri zahmetsiz bir şekilde gerçekleşerek hızlı ve benzersiz bir deneyim yaşanabilir.</p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/3sd.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item -->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">XRD Cihazı</h5>
                            <p class="font-italic text-muted mb-0 small">X-Işını Kırınım yöntemi (XRD), her bir kristal fazın kendine özgü atomik dizilimlerine bağlı olarak X-ışınlarını karakteristik bir düzen içerisinde kırması esasına dayanır. Her bir kristal faz için bu kırınım profilleri bir nevi parmak izi gibi o kristali tanımlar. X-Işını Kırınım analiz metodu, analiz sırasında numuneyi tahrip etmez ve çok az miktardaki numunelerin dahi analizlerinin yapılmasını sağlar.</p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/xrd.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item -->
               
            </ul> <!-- End -->
        </div>
    </div>

</div>
    
</template>

<script>
    export default {

    }
</script>

<style scoped>
#cars-slider {
  height: 250px;
  background: url("@/img/eng.jpg") center center no-repeat;
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
body {
    background: linear-gradient(to right, #c04848, #480048);
    min-height: 100vh
}

.text-gray {
    color: #aaa
}

img {
    height: 170px;
    width: 140px
}
</style>