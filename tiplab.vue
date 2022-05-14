<template>
<div>
    
    <div class="pb-5"><Navbar /></div>
    
    
     <section id="cars-slider" class="slider">
        <div id="cars-caption" class="caption">
            <h1>Tıp Fakültesi Laboratuvarı</h1>
            <p>Üniversitemiz öğrencileri okulumuzun son teknolojiyle donatılmış laboratuvarlarından faydalanabilirler.</p>

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
                            <h5 class="mt-0 font-weight-bold mb-2">Doku Takip Cihazı
</h5>
                            <p class="font-italic text-muted mb-0 small">MTM II, dokuların hızlı takibi, biyopsilerin hızlı işlenmesi ve her histoloji laboratuvarının gece boyunca toplu doku işleme ihtiyaçları için uygun maliyetli ve kullanıcı dostu bir alternatif sunar.</p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/doku-takip.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item-->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Frozen</h5>
                            <p class="font-italic text-muted mb-0 small">  kullanıcıya toxic gazların ulaşmasına engel olan çok kuvvetli bir emiş sistemine sahip Workstain BX serisi; sıvı geçirmez monitör ve klavyeden oluşan Görüntülü ve Sesli kayıt sistemine sahip Macropath Sistemi ile donatılmış, yüksekliği ayarlanabilen bir sistemdir.</p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/frozen.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item -->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Mikrotom</h5>
                            <p class="font-italic text-muted mb-0 small">Mikrotom, alınan doku örneklerinin son derece ince bir şekilde kesilerek incelenmesine imkân tanıyan kesme aracıdır.</p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/vet.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item -->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Sitoloji </h5>
                            <p class="font-italic text-muted mb-0 small"> Otomatik Yayma ve Boyama Cihazı Lam Yayma yüksek kalite ve standardizasyonun sağlanması için otomatize edilmiştir. Aynı anda birden fazla preparatının hazırlanmasına uygundur</p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/sitoloji.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
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
  background: url("@/img/bio.jpg") center center no-repeat;
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