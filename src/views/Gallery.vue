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
                  <h3 class="title">GALERİ</h3>
    
                          <a href="" class="text-dark"><h3 class="md-title" style ="font-family: Lucida Handwriting; font-weight: 700	">Sizin İçin</h3></a>
                  
                </div>
              </div>
            </div>
          </div>

          <div class="profile-tabs">
            <tabs
              :tab-name="['Kapı', 'Merdiven', 'Korkuluk']"
              :tab-icon="['camera', 'palette', 'work']"
              plain
              nav-pills-icons
              color-button="success"
            >
              <template slot="tab-pane-1">
                <div class="md-layout">
                  <div class="md-layout-item md-size-50 ml-auto">
                    <img :src="tabPane1[0].image" class="rounded" />
                    <img :src="tabPane1[1].image" class="rounded" />
                    <img :src="tabPane1[2].image" class="rounded" />
                  </div>
                  <div class="md-layout-item md-size-50 mr-auto">
                    <img :src="tabPane1[3].image" class="rounded" />
                    <img :src="tabPane1[4].image" class="rounded" />
                    <img :src="tabPane1[5].image" class="rounded" />
                  </div>
                </div>
              </template>
              <template slot="tab-pane-2">
                <div class="md-layout">
                  <div class="md-layout-item md-size-50 ml-auto">
                    <img :src="tabPane2[0].image" class="rounded" />
                    <img :src="tabPane2[1].image" class="rounded" />
                    <img :src="tabPane2[2].image" class="rounded" />
                  </div>
                  <div class="md-layout-item md-size-50 mr-auto">
                    <img :src="tabPane2[3].image" class="rounded" />
                    <img :src="tabPane2[4].image" class="rounded" />
                    <img :src="tabPane2[5].image" class="rounded" />
                  </div>
                </div>
              </template>
              <template slot="tab-pane-3">
                <div class="md-layout">
                  <div class="md-layout-item md-size-50 ml-auto">
                    <img :src="tabPane3[0].image" class="rounded" />
                    <img :src="tabPane3[1].image" class="rounded" />
                    <img :src="tabPane3[2].image" class="rounded" />
                  </div>
                  <div class="md-layout-item md-size-50 mr-auto">
                    <img :src="tabPane3[3].image" class="rounded" />
                    <img :src="tabPane3[4].image" class="rounded" />
                    <img :src="tabPane3[5].image" class="rounded" />
                  </div>
                </div>
              </template>
            </tabs>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { Tabs } from "@/components";
export default {
  components: {
    Tabs
  },
  bodyClass: "profile-page",
  data() {
    return {
      tabPane1: [
        { image: require("@/assets/img/kapi/k11.png") },
        { image: require("@/assets/img/kapi/k24.png") },
        { image: require("@/assets/img/kapi/k10.png") },
        { image: require("@/assets/img/kapi/k13.png") },
        { image: require("@/assets/img/kapi/k14.png") },
        { image: require("@/assets/img/kapi/k16.png") },
      ],
      tabPane2: [
        { image: require("@/assets/img/merdiven/m9.png") },
        { image: require("@/assets/img/merdiven/m12.png") },
        { image: require("@/assets/img/merdiven/m11.png") },
        { image: require("@/assets/img/merdiven/m5.png") },
        { image: require("@/assets/img/merdiven/m6.png") },
        { image: require("@/assets/img/merdiven/m13.png") }
      ],
      tabPane3: [
        { image: require("@/assets/img/korkuluk/ko1.png") },
        { image: require("@/assets/img/korkuluk/ko2.png") },
        { image: require("@/assets/img/korkuluk/ko3.png") },
        { image: require("@/assets/img/korkuluk/ko12.png") },
        { image: require("@/assets/img/korkuluk/ko5.png") },
        { image: require("@/assets/img/korkuluk/ko10.png") },
      ]
    };
  },
  props: {
    header: {
      type: String,
      default: require("@/assets/img/header/galleri-header.jpg")
    },
    img: {
      type: String,
      default: require("@/assets/img/home/favicon.png")
    }
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
</style>
