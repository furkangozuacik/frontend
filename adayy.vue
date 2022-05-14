<script>
import { library } from '@fortawesome/fontawesome-svg-core'

import { faHatWizard } from '@fortawesome/free-solid-svg-icons'

import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
</script>

<script src="https://kit.fontawesome.com/c73651798c.js" crossorigin="anonymous"></script>
<template>
<div>
    
    <div class="pb-5"><Navbar /></div>
    
    
     <section id="about">
        <div class="container">
             <div class="row">

                  <div class="col-md-6 col-sm-12">
                       <div class="about-info">
                            <h2>Aday Öğrenci Portalı</h2>
                            <hr>

                            <figure>
                                 <figcaption>
                                      <h3>Yandaki formu doldurarak üniversitemiz hakkında bilgi alabilirsiniz.</h3>
                                      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sint ipsa voluptatibus.</p>
                                 </figcaption>
                            </figure>

                            <figure>
                                 <figcaption>
                                      <h3>Mail yoluyla ulaşabilirsiniz.</h3>
                                      <p><a href="mailto:adayogrenci@edu.tr">adayogrenci@edu.tr</a></p>
                                 </figcaption>
                            </figure>

                            <figure>
                                 <figcaption>
                                      <h3>Mesai saatlerinde arayabilirsiniz.</h3>
                                      <p>Telefon Numaramız: (0212)4481712</p>
                                 </figcaption>
                            </figure>
                       </div>
                  </div>

                  <div class="col-md-offset-1 col-md-4 col-sm-12">
                       <div class="entry-form">
                            <form action="#" method="post">
                                 <h2>Hemen Bilgi Al</h2>
                                 <input type="text" name="full name" class="form-control" placeholder="Full name" required="">

                                 <input type="email" name="email" class="form-control" placeholder="Your email address" required="">

                                 

                                 <button class="submit-btn form-control" id="form-submit">Başla</button>
                            </form>
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
#cars-slider {
  height: 250px;
  background: url("@/img/arastirma-merkezi.jpg") center center no-repeat;
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
    color: black;
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

#about figure {
    display: inline-block;
    vertical-align: top;
    margin-left: 15px;
  }

  #about figure span {
    float: left;
    margin-left: -15px;
    padding: 15px 20px;
    position: relative;
    top: 20px;
  }

 
  
    a {
    color: #252525;
    transition: 0.5s;
    text-decoration: none !important;
  }

  a,
  input, button,
  .form-control {
    -webkit-transition: 0.5s;
    transition: 0.5s;
  }

  a:hover, a:active, a:focus {
    color: #29ca8e;
    outline: none;
  }

  


  .section-title {
    padding-bottom: 40px;
  }

  .section-title h2 {
    margin: 0;
  }

  .section-title small {
    display: block;
  }

  .overlay {
    background: rgba(20,20,20,0.5);
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }

  .entry-form {
    background: #252020;
    border-radius: 100%;
    text-align: center;
    padding: 6em;
    width: 450px;
    height: 450px;
  }

  .entry-form h2 {
    color: #ffffff;
    margin: 0;
  }

  .entry-form .form-control {
    background: transparent;
    border: 0;
    border-bottom: 1px solid;
    border-radius: 0;
    box-shadow: none;
    height: 45px;
    margin: 10px 0;
  }

  .entry-form .submit-btn {
    background: #ffffff;
    border-radius: 50px;
    border: 0;
    color: #252020;
    width: 50%;
    height: 50px;
    margin: 30px auto;
    margin-bottom: 10px;
  }

  .entry-form .submit-btn:hover {
    background: #3f51b5;
    color: #ffffff;
  }

  section {
    position: relative;
    padding: 100px 0;
  }
</style>