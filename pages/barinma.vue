<template>
<div>
    
    <div class="pb-5"><Navbar /></div>
    
    
     <section id="cars-slider" class="slider">
        <div id="cars-caption" class="caption">
            <h1>Barınma</h1>

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
                            <h5 class="mt-0 font-weight-bold mb-2">Lorem Ipsum Üniversitesi Yurtları</h5>

                            <p class="font-italic text-muted mb-0 small">
                                MEHMET GENÇ KÜLLİYESİ ÖĞRENCİ YURTLARI<br>HANDAN ERTUĞRUL KIZ ÖĞRENCİ YURDU
                                <br>GÖZTEPE YERLEŞKESİ YURTLARI  <br>ÖZMEN AKTAR KIZ ÖĞRENCİ YURDU
                            </p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/yurt.jpg" alt="Avcılar Yerleşkesi" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item-->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Yurtlarımızdan Görüntüler</h5>
                          
                        </div><img src="@/img/y1.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    <img src="@/img/y2.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    <img src="@/img/y5.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    
                    </div> <!-- End -->
                </li> <!-- End -->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Sık Sorulan Sorular</h5>
                            <p class="font-italic text-muted mb-0 small">
                                <b>* Yurt başvuruları ne zaman yapılacak?</b><br>Başvuruları ÖSYM tarafından YKS Yerleştirme sonuçları açıklandıktan sonra yapılması planlanmaktadır. Üniversitemiz sayfalarından duyuru yapılacaktır.

<br><b>* Yurt başvurusu genel şartları nelerdir?</b>

<br>Üniversitemiz yurtlarına başvuru yapabilmek için İstanbul Büyükşehir Belediyesi sınırları dışında ikamet etmek, ara sınıf öğrencileri için alt sınıflarda başarısız dersi olmamak şartı aranmaktadır.

<br><b>* Başvurular hangi yöntemle yapılacak?</b>

<br>Üniversitemiz yurt başvuruları internet üzerinden yapılmaktadır. Başvuru süreci başladığında ilgili linkler ilan edilecektir. 

<br><b>Yurt Müdiresi:</b> Nazire İPEK

<br><b>Telefon:</b> +90 (216) 777 1360 / 1361 / 1372 / 1375

<br><b>Email:</b> sks@loremipsum.edu.tr
                                </p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div></div> <!-- End -->
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