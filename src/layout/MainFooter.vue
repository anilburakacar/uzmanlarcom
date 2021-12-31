<template>
  <footer
          class="text-center text-lg-start text-light foter"
          style="background-color: #ECEFF1"
         :class="{ [`footer-${type}`]: type }"
         :data-background-color="backgroundColor"
  >
    <!-- Section: Links  -->
    <section :style="headerStyle">
      <div class="container text-center text-md-start ">
        <!-- Grid row -->
        <div class="row mt-3">
          <!-- Grid column -->
          <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
            <!-- Content -->
            <h1 class="text-uppercase fw-bold text-light">UZMANLAR METAL</h1>
            <hr
                class="mb-4 mt-0 d-inline-block mx-auto"
                style="width: 60px; background-color: #7c4dff; height: 2px"
                />
            <p>
              Firmamız 1995 yılında ÖZKARAOĞLU DEMİR DOĞRAMA Atölyesi olarak faliyetine
               başlamış birçok projelerde bulunmuşdur. Uygulamış olduğu projelerde kaliteden ve nitelikte ödün vermeden zamanında teslim etmiştir.
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-3 col-lg-3 col-xl-3 mx-auto mb-4 ">
            <!-- Links -->
            <h3 class="text-uppercase fw-bold bold-text">Menü</h3>
            
            <p>
              <a href="#/about" class="text-light">Hakkımızda</a>
            </p>
            <p>
              <a href="#/contact" class="text-light">İletişim</a>
            </p>
            <p>
              <a href="#/gallery" class="text-light">Galeri</a>
            </p>
       <br>

             <h3 class="text-uppercase fw-bold">E POSTA</h3>
            <p><i class="fas fa-envelope mr-3"></i> uzmanlarmetal@ttmail.com</p>
            <p><i class="fas fa-envelope mr-3"></i> uzmanlarmetal@icloud.com</p>
      
          
   
   
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
            <!-- Links -->
            <h3 class="text-uppercase fw-bold">Konum</h3>
         
            <p>
              <a href="" class="text-light">Yeniçamlıca Mahallesi Reşitpaşa Caddesi Aysel Sokak NO:39/A  
Ataşehir/İstanbul</a>
            </p>
         <br><br>
             <h3 class="text-uppercase fw-bold">İLETİŞİM</h3>
            <p><i class="fas fa-phone mr-3"></i> +90 532 335 96 92</p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
      
          <!-- Grid column -->
        </div>
        <!-- Grid row -->
      </div>
       <div
         class="text-center p-3"
         style="background-color: rgba(0, 0, 0, 0.2)"
         >
     &copy; {{ year }}
      <a class="text-light" href="https://www.instagram.com/anilburakacar_/"
         >Anıl Burak ACAR</a
        >
    </div>
    </section>
    <!-- Section: Links  -->

    <!-- Copyright -->
   

  </footer>




</template>
<script>
export default {
   props: {
    image: {
      type: String,
      default: require("@/assets/img/home/footers.jpg")}
    },
    backgroundColor: String,
    type: String
    ,
  data() {
    return {
      year: new Date().getFullYear()
    };
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.image})`
      };
    }}}
</script>
<style scoped>


</style>
