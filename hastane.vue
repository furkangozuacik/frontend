<template>
<div>
    
    <div class="pb-5"><Navbar /></div>
    
    
     <section id="cars-slider" class="slider">
        <div id="cars-caption" class="caption">
            <h1>Hastaneler</h1>
            <p>Üniversitemiz öğrencileri okulumuzun hastane ve diş hekimliği bölümlerinden faydalanabilirler. </p>

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
                            <h5 class="mt-0 font-weight-bold mb-2">Lorem Universitesi Hastanesi
</h5>
                            <p class="font-italic text-muted mb-0 small">Öğrencilerimize sağlık hizmeti vermektedir. Temel amacı, öğrencilerimize, akademik ve idari bütün personelimize kapsamlı olarak, koruyucu sağlık hizmetleri dahil nitelikli “Temel Sağlık Hizmetleri” sunmaktır.

Mediko Sosyal Merkezlerimizde birinci basamak sağlık hizmetlerinin yerine getirilmesi için poliklinik hizmeti verilmektedir..</p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/hospital.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item-->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Lorem Ağız ve Diş Sağlığı Uygulama ve Araştırma Merkezi</h5>
                            <p class="font-italic text-muted mb-0 small"> Ağız ve Diş Sağlığı Uygulama ve Araştırma Merkezi bünyesinde diş sağlığı tedavisi hizmetleri hafta içi her gün 09:00-16:30 saatleri arasında verilmektedir.</p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/dis.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
                    </div> <!-- End -->
                </li> <!-- End -->
                <!-- list group item -->
                <li class="list-group-item">
                    <!-- Custom content-->
                    <div class="media align-items-lg-center flex-column flex-lg-row p-3">
                        <div class="media-body order-2 order-lg-1">
                            <h5 class="mt-0 font-weight-bold mb-2">Lorem Veterinerlik Fakültesi Hastanesi</h5>
                            <p class="font-italic text-muted mb-0 small">Öğrencilerimiz evcil hayvanlarını veterinerlik fakültemizde tedavi ettirebilir.</p>
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
                            <h5 class="mt-0 font-weight-bold mb-2">Psikolojik Danışma ve Rehberlik  Merkezi </h5>
                            <p class="font-italic text-muted mb-0 small">Psikolojik danışmanlık, alanda eğitimli bir uzmanla danışan arasında gerçekleştirilen birebir görüşmelerden oluşmaktadır. Bireysel danışma, danışanla birlikte ilerleyen, güven duygusuyla gelişen, genellikle haftada bir gün ve ortalama 50 dakika süren bir psikolojik yardım ilişkisidir. Bireysel danışmada danışanın ihtiyaç duyduğu herhangi bir konu üzerine odaklanılabilir ve birlikte belirlenen hedeflere ulaşmak için çalışılır.</p>
                            <div class="d-flex align-items-center justify-content-between mt-1">
                                
                            </div>
                        </div><img src="@/img/psiko.jpg" alt="Generic placeholder image" width="200" class="ml-lg-5 order-1 order-lg-2">
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
  background: url("@/img/bogaz.jpg") center center no-repeat;
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