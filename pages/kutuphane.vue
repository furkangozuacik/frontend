<template>
<div>
    
    <div class="pb-5"><Navbar /></div>
    
    
     <section id="cars-slider" class="slider">
        <div id="cars-caption" class="caption">
            <h1>Kütüphane</h1>

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
                            <h5 class="mt-0 font-weight-bold mb-2">Merkez Kütüphane</h5>
                            <p class="font-italic text-muted mb-0 small">Merkez kütüphanemiz Göztepe kampüsümüzde bütün
                                bölümlerden öğrencilerimize hizmet vermektedir. 10000 kişi kapasitesi,
                                konforlu çalışma alanı ve zengin dokümatasyonu ile bütün öğrencilerimiz Merkez Kütüphanemizden yararlanabilir.
                                <br><b>Adres:</b>Lorem Ipsum Üniversitesi Goztepe Yerleşkesi Alkent 2000 Mah. Yiğittürk Cad. No:5/9/1 Kadıköy/İstanbul
                                <br><b>Telefon:</b>+90 (212) 404 03 00
                                <br><b>Faks:</b>+90 (212) 404 03 03
                                <br><b>*kütüphanemizin çalışma salonları 7/24 açıktır.</b>
                            </p>
                            <div class="d-flex align-items-center justify-content-between mt-1"></div>
                        </div><img src="@/img/merkezkutup.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item-->
                
                <!-- list group item -->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Birim Kütüphaneleri</h5>
                            <p class="font-italic text-muted mb-0 small"><br>Eczacılık Fakültesi Kütüphanesi
                            <br>Tıp Fakültesi Kütüphanesi
                            <br>Prof. Dr. Orhan Oğuz Kütüphanesi
                            <br>Eğitim ve Araştırma Hastanesi Kütüphanesi
                            <br>Menza Çalışma Salonu
                            <br>Mehmet Genç Külliyesi Kütüphanesi
                            <br>İlahiyat Fakültesi Kütüphanesi
                            <br>Hukuk ve İletişim Fakültesi Kütüphanesi
                            <br>Güzel Sanatlar Fakültesi Kütüphanesi
                            <br>Mühendislik Fakültesi Kütüphanesi
                            </p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/kutuphane.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
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
  background: url("@/img/iuc2.jpg") center center no-repeat;
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