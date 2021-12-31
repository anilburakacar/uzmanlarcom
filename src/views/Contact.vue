<template>
  <div class="wrapper">
    <parallax
      class="section page-header header-filter"
      :style="headerStyle"
    ></parallax>
    <div class="main main-raised">
      <div class="section profile-content">
        <div class="container">
          <div class="md-layout">
            <div class="md-layout-item md-size-50 mx-auto">
              <div class="profile">
                <div class="avatar">
                  <img
                    :src="img"
                    alt="Circle Image"
                    class="img-raised rounded-circle img-fluid"
                  />
                </div>
                <div class="name">
                  <h3 class="title">İLETİŞİM</h3>
                                           <a href="" class="text-dark"><h3 class="md-title" style ="font-family: Lucida Handwriting; font-weight: 700	">Sizin İçin</h3></a>

                </div>
              </div>
            </div>
          </div>

       
        </div>
      </div>

      <div class="section">
        <div class="container">
          <div class="md-layout text-center" >
            <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="info">
                  <div class="icon icon-info">
                    <i class="fas fa-map-marker-alt"></i>
                  </div>
                  <h4 class="info-title">KONUM</h4>
                  <p class="text-dark">
                   Yeniçamlıca Mahallesi Reşitpaşa Caddesi Aysel Sokak NO:39/A  
Ataşehir/İstanbul
                  </p>
                </div>
              </div>
            
          </div>

          
          <div class="features text-center">
            <div class="md-layout">
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="info" >
                  <a href="https://api.whatsapp.com/send?phone=905323359692&text=">
                  <div class="icon icon-success">
                    <i class="fab fa-whatsapp"></i>
                  </div>
                  <h4 class="info-title">WhatsApp</h4>
                  <p>
                    
                  </p>
                  </a>
                </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="info">
                  <a href="https://www.instagram.com/uzmanlarmetal/">
                  <div class="icon icon-danger">
                    <i class="fab fa-instagram"></i>
                  </div>
                  <h4 class="info-title">Instagram</h4>
                  <p>
                    
                  </p>
                  </a>  
                </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="info">
                  <a href="https://www.facebook.com/vahdettin.karaoglu/">
                  <div class="icon icon-info">
                    <i class="fab fa-facebook"></i>
                  </div>
                  <h4 class="info-title">Facebook</h4>
                  <p>
                   
                  </p>
                  </a>  
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
     
      <div class="section section-contacts">
        <div class="container">
          <div class="md-layout">
            <div class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto text-center">
              <i class="far fa-envelope-open fa-5x" ></i>
              <h2 class="text-center title">Hizmet Aşamasında</h2>
              <h4 class="text-center description">
                
              </h4>
              <form class="contact-form">
                <div class="md-layout">
                  <div class="md-layout-item md-size-50">
                    <md-field>
                      <label>Adınız</label>
                      <md-input v-model="name" type="text"></md-input>
                    </md-field>
                  </div>
                  <div class="md-layout-item md-size-50">
                    <md-field>
                      <label>E-Mail</label>
                      <md-input v-model="email" type="email"></md-input>
                    </md-field>
                  </div>
                </div>
                <md-field maxlength="5">
                  <label>Mesajınız</label>
                  <md-textarea v-model="message"></md-textarea>
                </md-field>
                <div class="md-layout">
                  <div class="md-layout-item md-size-33 mx-auto text-center">
                    <md-button class="md-success">Gönder</md-button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
      
    </div>
    
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1505.9075045387908!2d29.16615536204813!3d40.98553144963804!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x14cacf66e9ceaf29%3A0x1c1f8f4149c88666!2zWWVuaSDDh2FtbMSxY2EsIEF5c2VsIFNrLiAzOSBBLCAzNDg4OCBEdWR1bGx1IE9zYi9BdGHFn2VoaXIvxLBzdGFuYnVs!5e0!3m2!1str!2str!4v1633861609947!5m2!1str!2str" frameborder="0" style="border:0; width: 100%; height: 400px;" allowfullscreen=""></iframe>
  </div>
</template>

<script>
export default {
  bodyClass: "profile-page",

  props: {
    header: {
      type: String,
      default: require("@/assets/img/header/iletisim-header.jpg")
    },
    img: {
      type: String,
      default: require("@/assets/img/home/favicon.png")
    },
  },
    data() {
    return {
      name: null,
      email: null,
      message: null
    };
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.header})`
      };
    }
  }
};
</script>

<style lang="scss" scoped>
.section {
  padding: 0;
}

.profile-tabs::v-deep {
  .md-card-tabs .md-list {
    justify-content: center;
  }

  [class*="tab-pane-"] {
    margin-top: 3.213rem;
    padding-bottom: 50px;

    img {
      margin-bottom: 2.142rem;
    }
  }
}

.md-card-actions.text-center {
  display: flex;
  justify-content: center !important;
}
.contact-form {
  margin-top: 30px;
}

.md-has-textarea + .md-layout {
  margin-top: 15px;
}
</style>
