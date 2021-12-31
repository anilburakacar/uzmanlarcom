<template>
  <div class="wrapper">
    <!--HEADER-->
   <parallax class="section page-header header-filter" :style="headerStyle">
      <div class="container">
        <div class="md-layout">
          <div
            class="md-layout-item md-size-50 md-small-size-70 md-xsmall-size-100 text-center"
          >
            <h1 class="title text-center">Uzmanlar Metal</h1>
            <h3 class="text-center">İnşaat Denizcilik Turizm Gıda San. ve Tic. Ltd. Şti.</h3>
            <h4 class="">
          Şirketimiz müşterilerimizin beklentilerini ürün ve hizmetlerinde farklılaşarak
          kurum ve kişiler ile uyum içerisine çalışarak gerçekleştirmeyi amaçlar.
            </h4>
            <br />
            <md-button
              href="#/contact"
              class="md-success md-lg"
              ><i class="fas fa-play"></i>İletişim' geçin</md-button
            >
          </div>
        </div>
      </div>
    </parallax>

  <!--SECTİON-->
    <div class="main main-raised">
     
      <!--SECTİON 2-->
      <div class="section section-javascript">
        <div class="container">
          <javascript-components></javascript-components>
        </div>
      </div>
      <!--SECTİON 1-->
      <div class="section section-white">
        <div class="container">
          <nav-pills></nav-pills>
        </div>
      </div>
       <!--SECTİON 4-->
    
      <!--SECTİON 5-->
  
      <!--SECTİON 6-->
      <div class="md-layout">
        <div class="md-layout-item text-center">
          <md-button href="" class="md-simple md-success md-lg">
            <a href="#/gallery"><h5>Galerimize Göz atın</h5></a>
          </md-button>
        </div>
      </div>
      <!--SECTİON 7-->
      <div class="section section-examples">
        <div class="container-fluid text-center">
          <div class="md-layout">
            <div class="md-layout-item">
              <a href="" target="">
                <img
                  :src="landing"
                  alt="Rounded Image"
                  class="img-raised rounded img-fluid"
                />
              </a>
            </div>
            <div class="md-layout-item">
              <a href="" target="">
                <img
                  :src="profile"
                  alt="Rounded Image"
                  class="img-raised rounded img-fluid"
                />
              </a>
            </div>
          </div>
        </div>
      </div>
      <!--SECTİON 8-->
       <div class="section section-examples">
        <div class="container-fluid text-center">
          <div class="md-layout">
            <div class="md-layout-item">
              <a href="" target="">
                <img
                  :src="profile1"
                  alt="Rounded Image"
                  class="img-raised rounded img-fluid"
                />
              </a>
            </div>
            <div class="md-layout-item">
              <a href="" target="">
                <img
                  :src="profile2"
                  alt="Rounded Image"
                  class="img-raised rounded img-fluid"
                />
              </a>
            </div>
            <div class="md-layout-item">
              <a href="" target="">
                <img
                  :src="profile3"
                  alt="Rounded Image"
                  class="img-raised rounded img-fluid"
                />
              </a>
            </div>
             <div class="md-layout-item">
              <a href="" target="">
                <img
                  :src="profile4"
                  alt="Rounded Image"
                  class="img-raised rounded img-fluid"
                />
              </a>
            </div>
          </div>
        </div>
      </div>
        <div class="section section-examples">
        <div class="container-fluid text-center">
          <div class="md-layout">
            <div class="md-layout-item">
              <a href="" target="">
                <img
                  :src="landing1"
                  alt="Rounded Image"
                  class="img-raised rounded img-fluid"
                />
              </a>
            </div>
            <div class="md-layout-item">
              <a href="" target="">
                <img
                  :src="landing2"
                  alt="Rounded Image"
                  class="img-raised rounded img-fluid"
                />
              </a>
            </div>
            <div class="md-layout-item">
              <a href="" target="">
                <img
                  :src="landing3"
                  alt="Rounded Image"
                  class="img-raised rounded img-fluid"
                />
              </a>
            </div>
          </div>
        </div>
      </div>
      <!--SECTİON 9-->
      <div class="section section-download" id="downloadSection">
        <div class="container">
          <div class="md-layout text-center">
            <div class="md-layout-item md-size-66 md-small-size-100 mx-auto">
              <h2>Şirketimiz</h2>
              <h3>
                müşterilerimizin beklentilerini ürün ve hizmetlerinde farklılaşarak
          kurum ve kişiler ile uyum içerisine çalışarak gerçekleştirmeyi amaçlar.
              </h3>
            </div>
            <div class="md-layout-item md-size-50 md-small-size-100 mx-auto">
              <md-button
                href="#/contact"
                class="md-info md-lg"
                ><i class="fab fa-html5"></i> İletişime geçin</md-button
              >
              <md-button
                href="#/gallery"
                class="md-danger md-lg"
                ><i class="fab fa-wordpress"></i> Galeriye göz atın</md-button
              >
            </div>
          </div>

          <br /><br />
          
 <div class="section text-center">
        <div class="container">
          <h2 class="title">Referanslar</h2>
          <div class="team">
            <div class="md-layout">
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg1"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      
                      <br />
                      <small class="card-description text-muted"></small>
                    </h4>

                    <md-card-content>
                      <h4 class="text-dark font-weight-bold text-muted">
                        AYDIN GROUP / AYDIN RESİDENCE / YENİKÖY <br>
                        AYDIN GROUP / CEM PLAZA / ŞİŞLİ <br>
                        AYDIN GROUP / KENAN/EMRE ÖZEL İNŞAATI / GÜMÜŞSUYU <br>
                        BARKINAY MİMARLIK İNŞAAT TAAHÜT SAN VE TİC LTD ŞTİ <br>
                        BİLKAR ULUSLAR ARASI NAKLİYATGÜMRÜK DIŞ TİC LTD ŞTİ <br>
                        CAFER BOZKURT MİMARLIK LTD ŞTİ <br>
                      </h4>
                    </md-card-content>

                  </md-card>
                </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg2"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <br>
                    <h4 class="card-title">
                      Referanslarımızın Bazıları
                      <br />
                      <small class="card-description text-muted"
                        ></small
                      >
                    </h4>

                    <md-card-content>
                       <h4 class="text-dark font-weight-bold text-muted">
                      ALTINCI DUYU REKLAM FİLM VE KOMİNİKASYAN TİC A.Ş <br>
                      ARMO MOBİLYA VE TİCARET LTD ŞTİ <br>
                      AS İMAR VE TİC LTD ŞTİ <br>
                      ASYA NAKLİYAT TİC LTD ŞTİ
                      AYDIN GROUP / ARNAVUTKÖY KONUTLARI / ARNAVUTKÖY <br>
                      AYDIN GROUP / AYDIN KONUTLARI / SUDİYE <br>
                      EREN HOLDİNG A.Ş <br>
                      </h4>
                    </md-card-content>

                   
                  </md-card>
                </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg3"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      
                      <br />
                      <small class="card-description text-muted"></small>
                    </h4>

                    <md-card-content>
                       <h4 class="text-dark font-weight-bold text-muted">
                        ÇAĞDAŞ MÜHENDİSLİK METOLOJİ MAKİNA SAN TİC LTD ŞTİ <br>
                        CEMİL MOLLA YALISI <br>
                        D.K TASARIM MİMARLIK DEKARASYON SAN VE TİC LTD ŞTİ <br>
                        DEĞER İNŞAAT SAN VE TİC LTD ŞTİ <br>
                        DEMİRER KABLO TES. SAN VE TİC A.Ş <br>
                        DENİZ AŞIRI TURİZM OTELCİLİK İŞLETMELER. A.Ş <br>
                        E DESİGN STUDIO TASARIM MİMARLIK MÜH.REKLAM <br>
                      </h4>
                    </md-card-content>

                   
                  </md-card>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
         
     
  <!--SECTİON 7-->
      <div class="section section-examples">
        <div class="container-fluid text-center">
          <h3 class="text-center" style ="font-family: Lucida Handwriting; font-weight: 600	">Fark yaratın </h3>
          <hr>
          <div class="md-layout">
            
            <div class="md-layout-item">
              <a href="" target="">
                <img
                  :src="son1" style="height:400px; width:450px;"
                  alt="Rounded Image"
                  class="img-raised rounded img-fluid"
                />
              </a>
            </div>
            <div class="md-layout-item">
              <a href="" target="">
                <img
                  :src="son2" style="height:400px; width:450px;"
                  alt="Rounded Image"
                  class="img-raised rounded img-fluid"
                />
              </a>
            </div>
          </div>
        </div>
      </div>

     
        </div>
      </div>
    </div>
  </div>
</template>

<script>
//import Tabs from "./components/TabsSection";
import NavPills from "./components/NavPillsSection";
import JavascriptComponents from "./components/JavascriptComponentsSection";

export default {
  components: {
   // Tabs,
    NavPills,
    JavascriptComponents,
  },
  name: "index",
  bodyClass: "index-page",
  props: {
    image: {
      type: String,
      default: require("@/assets/img/header/index-header.png")
    },
    signup: {
      type: String,
      default: require("@/assets/img/merdiven/m7.png")
    },
    landing: {
      type: String,
      default: require("@/assets/img/kapi/k4.png")
    },
    profile: {
      type: String,
      default: require("@/assets/img/kapi/k14.png")
    },

    profile1: {
      type: String,
      default: require("@/assets/img/merdiven/m13.png")
    },
    profile2: {
      type: String,
      default: require("@/assets/img/merdiven/m6.png")
    },
    profile3: {
      type: String,
      default: require("@/assets/img/merdiven/m9.png")
    },
    profile4: {
      type: String,
      default: require("@/assets/img/merdiven/m12.png")
    },


    landing1: {
      type: String,
      default: require("@/assets/img/kutuphane/ku2.png")
    },
    landing2: {
      type: String,
      default: require("@/assets/img/kutuphane/ku3.png")
    },
    landing3: {
      type: String,
      default: require("@/assets/img/kutuphane/ku4.png")
    },


    son1: {
      type: String,
      default: require("@/assets/img/karisik/s1.png")
    },
    son2: {
      type: String,
      default: require("@/assets/img/karisik/s4.png")
    },



     header: {
      type: String,
      default: require("@/assets/img/korkuluk/ko1.png")
    },
    teamImg1: {
      type: String,
      default: require("@/assets/img/home/referance.png")
    },
    teamImg2: {
      type: String,
      default: require("@/assets/img/home/referance.jpg")
    },
    teamImg3: {
      type: String,
      default: require("@/assets/img/home/referance.png")
    }
  },
  data() {
    return {
      firstname: null,
      email: null,
      password: null,
      leafShow: false
    };
  },
  methods: {
    leafActive() {
      if (window.innerWidth < 768) {
        this.leafShow = false;
      } else {
        this.leafShow = true;
      }
    }
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.image})`
      };
    },
    signupImage() {
      return {
        backgroundImage: `url(${this.signup})`
      };
    }
  },
  mounted() {
    this.leafActive();
    window.addEventListener("resize", this.leafActive);
  },
  beforeDestroy() {
    window.removeEventListener("resize", this.leafActive);
  }
};
</script>
<style lang="scss">
.section-download {
  .md-button + .md-button {
    margin-left: 5px;
  }
}

@media all and (min-width: 991px) {
  .btn-container {
    display: flex;
  }
}
</style>
