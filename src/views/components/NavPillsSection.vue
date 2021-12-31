<template>
  <div class="wrapper">
    <div id="navigation-pills">
      <div class="title text-center">
       
        <img src="../../assets/img/home/fav.png" style="width:200px; height:40px; border-radius:10px;">
      
      </div>
      <div class="title">
      </div>
      <div class="md-layout">
        <div class="md-layout-item md-size-100 md-small-size-100">
          <tabs
            :tab-name="['Ne zaman?', 'Ne yapıyor?']"
            :tab-icon="['dashboard', 'schedule']"
            plain
            flex-column
            nav-pills-icons
            color-button="primary"
          >
            <template slot="tab-pane-1">
             <h3 class=" font-weight-bold text-muted" style="font-size:20px;">
               Firmamız 1995 yılında ÖZKARAOĞLU DEMİR DOĞRAMA Atölyesi olarak faliyetine başlamış birçok projelerde bulunmuşdur.
            Uygulamış olduğu projelerde kaliteden ve nitelikte ödün vermeden  zamanında teslim etmiştir.
             </h3>
            </template>
            <template slot="tab-pane-2">
               <h3 class=" font-weight-bold text-muted" style="font-size:20px;">
          Yıllar geçtikçe piyasadaki gereksimler üzerine 2002 yılında UZMANLAR METAL İNŞAAT
            DENİZCİLİK TURİZM GIDA SAN.ve TİC.LTD.ŞTİ kurarak faliyetimizi devam ettirmekteyiz.
             </h3>
            </template>
          </tabs>
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
  }
};
</script>

<style lang="css"></style>
