<template>
  <div class="wrapper">
    <div id="nav-tabs">
      <h3 class="text-center">UZMANLAR METAL</h3>
      <br>
      <div class="md-layout">
        <div class="md-layout-item md-size-100 md-small-size-100">
          <nav-tabs-card no-label>
            <template slot="content">
              <md-tabs class="md-info"  md-alignment="left">
               

                <md-tab id="tab-pages" md-label="Ne zaman kuruldu?" md-icon="chat">
                    <h4>
            Firmamız 1995 yılında ÖZKARAOĞLU DEMİR DOĞRAMA Atölyesi olarak faliyetine başlamış birçok projelerde bulunmuşdur.
            Uygulamış olduğu projelerde kaliteden ve nitelikte ödün vermeden  zamanında teslim etmiştir.
       
                  </h4>
                </md-tab>

                <md-tab id="tab-posts" md-label="Ne yapıyor?" md-icon="build">
                    <h4>
                 Yıllar geçtikçe piyasadaki gereksimler üzerine 2002 yılında UZMANLAR METAL İNŞAAT
            DENİZCİLİK TURİZM GIDA SAN.ve TİC.LTD.ŞTİ kurarak faliyetimizi devam ettirmekteyiz.
                  </h4>
                </md-tab>
              </md-tabs>
            </template>
          </nav-tabs-card>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { NavTabsCard } from "@/components";

export default {
  components: {
    NavTabsCard
  }
};
</script>

<style lang="css"></style>
