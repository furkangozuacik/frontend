<template>
<div>
    
    <div class="pb-5"><Navbar /></div>
    
    
     <section id="cars-slider" class="slider">
        <div id="cars-caption" class="caption">
            <h1>Beslenme</h1>
            <p>Kampüste Beslenme</p>

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
                            <h5 class="mt-0 font-weight-bold mb-2">Kafeterya</h5>
                            <p class="font-italic text-muted mb-0 small"><b>Espresso Lab --</b> Avcılar Yerleşkesi
                                <br><b> SELFİŞ -- </b>Avcılar/Büyükçekmece Yerleşkesi
                                <br><b> KAHVE DÜNYASI --</b> Avcılar/Göztepe Yerleşkesi
                                <br><b> BAHÇE KAFE  --</b> Avcılar/Büyükçekmece Yerleşkesi
                                <br><b> STARBUCKS --</b> Göztepe Yerleşkesi</p>
                            <div class="d-flex align-items-center justify-content-between mt-1"></div>
                        </div><img src="@/img/esp.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item-->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Yemekhane</h5>
                            <p class="font-italic text-muted mb-0 small">Tüm kampüslerimizde bulunan yemekhanelerimizden günlük ortalama olarak 10 - 11 bin öğrencimiz faydalanmaktadır.

Avcılar, Büyükçekmece, Acıbadem, Göztepe Yerleşkelerimizde ise Aralık Aylarında yapılan yemek ihalesi ile 4 kap tabldot yemek satın alınmaktadır. Bu kampüslerden 2. Eğitim olanlarda hem öğle hem de akşam yemeği verilmektedir. Bütün kampüslerimizde verilen yemek hizmeti kontrolü daire başkanlığımız tarafından yapılmaktadır. </p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/yhane.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item -->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Sosyal Tesisler</h5>
                            <p class="font-italic text-muted mb-0 small">Tüm kampüslerimizde bulunan konukevlerimiz uzun yıllardan bu yana başta Lorem İpsum Üniversitesi mensupları olmak üzere diğer üniversite mensupları ve kamu çalışanları  için hizmet vermektedir.Odalarımızda televizyon, buzdolabı ve klima mevcuttur.
                                <br> <b>Telefon	:</b> 0216 777 41 90<br><b>Fax 	:</b> 0216 777 41 91
<br><b>E-mail	:</b> konukevi@loremipsum.edu.tr
                            </p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/sosyaltesis.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
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