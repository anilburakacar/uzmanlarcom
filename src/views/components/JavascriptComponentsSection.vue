<template>
  <div class="wrapper">
    <div id="javascriptComponents">
      <div class="title">
        <h3 class="text-center" style ="font-family: Lucida Handwriting; font-weight: 600	">Hayatınıza renk katın </h3>
      </div>
      <div class="md-layout">
        <div class="md-layout-item md-size-100 mx-auto md-small-size-100">
          <md-card>
            <carousel
              :per-page="1"
              loop
              :speed="700"
              autoplay
              :autoplay-timeout="5000"
              :mouse-drag="false"
              navigationEnabled
              navigationNextLabel="<i class='material-icons'>keyboard_arrow_right</i>"
              navigationPrevLabel="<i class='material-icons'>keyboard_arrow_left</i>"
            >
              <slide>
                <div class="carousel-caption">
                  <h3 class="text-light" style="font-weight:700px;">
                    
                  </h3>
                </div>
                <img :src="carousel1" alt="carousel1" style="height:750px;"/>
              </slide>
              <slide>
                <div class="carousel-caption">
                  <h3 class="text-light" style="font-weight:700px;">
                    
                  </h3>
                </div>
                <img :src="carousel2" alt="carousel2" style="height:750px;"/>
              </slide>
              <slide>
                <div class="carousel-caption">
                  <h3 class="text-light" style="font-weight:700px;">
                   
                  </h3>
                </div>
                <img :src="carousel3" alt="carousel3" style="height:750px;"/>
              </slide>
            </carousel>
          </md-card>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      classicModal: false,
      selectedDate: new Date("2018/03/26"),
      carousel1: require("@/assets/img/korkuluk/ko7.png"),
      carousel2: require("@/assets/img/korkuluk/ko10.png"),
      carousel3: require("@/assets/img/korkuluk/ko12.png")
    };
  },
  methods: {
    classicModalHide() {
      this.classicModal = false;
    }
  }
};
</script>
