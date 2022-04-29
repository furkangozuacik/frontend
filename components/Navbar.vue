<template>
    <div>
       
 <nav class="navbar navbar-expand-lg navbar-light bg-info pt-3 pb-3s">
   <div><img style="width: 50px; height: 50px;" src="@/img/github-icon.png" alt=""></div>
  <a class="navbar-brand ml-sm-5 display-1" href="#">Lorem Ipsum <br>University</a>
 <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button> 

  <div class="collapse navbar-collapse float-right justify-content-end" id="navbarSupportedContent">
    <ul class="navbar-nav float-right">
      
      
      <li class="nav-item active dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Akademik
        </a>
        <div class="dropdown-menu dropdown-content" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Fakülteler</a>
          <a class="dropdown-item" href="#">Enstitüler</a>
          <a class="dropdown-item" href="#">Yüksekokullar</a>
          <a class="dropdown-item" href="#">Meslek Yüksekokulları</a>
          
        </div>
      </li>
       <li class="nav-item active dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
         Kampüste Yaşam
        </a>
        <div class="dropdown-menu dropdown-content" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Beslenme</a>
          <a class="dropdown-item" href="#">Yerleşkeler</a>
          <a class="dropdown-item" href="#">Barınma</a>
          <a class="dropdown-item" href="#">Kütüphane</a>
          
        </div>
      </li>
       <li class="nav-item active dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Araştırma
        </a>
        <div class="dropdown-menu dropdown-content" aria-labelledby="navbarDropdown">
          <!--<NuxtLink to="/products" class="text-gray-900 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Products</NuxtLink> -->
          <NuxtLink to="/arastirma-merkezleri" class="dropdown-item">Araştırma Merkezleri</NuxtLink>
          <!--<a class="dropdown-item" href="#">Araştırma Merkezleri</a> -->
          <NuxtLink to="/arastirma-ve-projeler" class="dropdown-item">Araştırma ve Projeler</NuxtLink>
          <!--<a class="dropdown-item" href="#">Araştırma ve Projeler</a> -->
          <NuxtLink to="/bilgi-kaynaklari" class="dropdown-item">Bilgi Kaynakları</NuxtLink>
          <!--<a class="dropdown-item" href="#">Bilgi Kaynakları</a> -->
          
        </div>
      </li>
       <li class="nav-item active dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Hizmetler
        </a>
        <div class="dropdown-menu dropdown-content" aria-labelledby="navbarDropdown">
          <li><a class="dropdown-item" href="#">E-Hizmetler</a></li>
          <li><a class="dropdown-item" href="#">E-Bilgi servisi</a></li>
          <a class="dropdown-item" href="#">Laboratuvarlar</a>
          <a class="dropdown-item" href="#">Hastaneler</a>
          
        </div>
      </li>
      <li class="nav-item active">
        <a class="nav-link" href="#">Hakkımızda <span class="sr-only">(current)</span></a>
      </li>
      
    </ul>
    
  </div>
</nav>


  
    
    </div>
</template>



<script>
export default {
  
    
}

</script>


<style scoped>

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  padding: 12px 16px;
  z-index: 1;
}

.dropdown:hover .dropdown-content {
  display: block;
}
.navbar-nav {
  display: flex;
  justify-content: right;
  float:right;
}




.navbar-nav li a {
 
  font-size: 18px;
  letter-spacing: 1px;
  display: block;
  text-decoration: none;
  color: #333;
  transition: all 0.5s ease;
}
.navbar-nav li:hover  a{
  background: #c9e9f2;
  color: black;
  font-size: 16px;
}
.dropdown-contenet li:hover a {
  background: #840909;
  color: #333;
}
</style>
