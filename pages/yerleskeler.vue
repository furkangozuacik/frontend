<template>
<div>
    
    <div class="pb-5"><Navbar /></div>
    
    
     <section id="cars-slider" class="slider">
        <div id="cars-caption" class="caption">
            <h1>Yerleşkeler</h1>

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
                            <h5 class="mt-0 font-weight-bold mb-2">Lorem Ipsum Üniversitesi Avcılar Yerleşkesi</h5>

                            <p class="font-italic text-muted mb-0 small">
                                Rektörlük<br>Mühendislik Fakültesi
                                <br>Veteriner Fakültesi <br>Çevre ve Yer Bilimleri Uygulama ve Araştırma Merkezi
                            <br><b>Adres:</b> Lorem Ipsum Üniversitesi Avcılar Yerleşkesi 34320  Avcılar/İstanbul
                            </p>
                            <p class="font-italic text-muted mb-0 small"><b>Tel:</b> +90 (212) 404 03 00 <br><b>Faks:</b> +90 (212) 404 07 01</p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/avcilar.jpg" alt="Avcılar Yerleşkesi" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item-->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Lorem Ipsum Üniversitesi Büyükçekmece Yerleşkesi</h5>
                            <p class="font-italic text-muted mb-0 small">
                                Rektörlük Çalışma Ofisi<br>Hemşirelik Fakültesi
                                <br>Eğitim Fakültesi <br> Tıp Fakültesi
                    <br><b>Adres:</b> Lorem Ipsum Üniversitesi Büyükçekmece Yerleşkesi Alkent 2000 Mah. Yiğittürk Cad. No:5/9/1 Büyükçekmece/İstanbul 
                            </p>
                            <p class="font-italic text-muted mb-0 small"><b>Tel:</b> +90 (212) 404 03 00 <br><b>Faks:</b>+90 (212) 866 37 30</p>

                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/bcekmece.png" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Lorem Ipsum Üniversitesi Acıbadem Yerleşkesi</h5>
                            <p class="font-italic text-muted mb-0 small">
                                Güzel Sanatlar Fakültesi<br>Güzel Sanatlar Enstitüsü  
                                <br>İlâhiyat Fakültesi<br>İktisat Fakültesi
                                <br><b>Adres:</b> Lorem Ipsum Üniversitesi Acıbadem Yerleşkesi Alkent 2000 Mah. Yiğittürk Cad. No:5/9/1 Acıbadem/İstanbul</p>
                            <p class="font-italic text-muted mb-0 small"><b>Tel:</b> +90 (212) 404 03 00 <br><b>Faks:</b> +90 (212) 866 37 30</p>

                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/acıbadem.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Lorem Ipsum Üniversitesi Goztepe Yerleşkesi</h5>
                            <p class="font-italic text-muted mb-0 small">
                                Spor Bilimleri Enstitüsü<br>Türkiyat Araştırmaları Enstitüsü
 <br>İslam Ekonomisi ve Finansı Enstitüsü<br>Sürekli Eğitim Merkezi
 <br>Uzaktan Eğitim Merkezi<br>Orta Doğu ve İslam Ülkeleri Araştırmaları Enstitüsü
 <br>Sosyal Bilimler Enstitüsü<br>Bankacılık ve Sigortacılık Enstitüsü
                            <br><b>Adres:</b> Lorem Ipsum Üniversitesi Goztepe Yerleşkesi Alkent 2000 Mah. Yiğittürk Cad. No:5/9/1 Kadıköy/İstanbul </p>
                            <p class="font-italic text-muted mb-0 small"><b>Tel:</b> +90 (212) 404 03 00 <br><b>Faks:</b> +90 (212) 866 37 30</p>

                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/goztepe.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item -->
                
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