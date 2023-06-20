<template>
  <div class="section section-tabs">
    <div class="container">
      <div class="row">
        <div class="col-md-10 ml-auto col-xl-6 mr-auto">
          <p class="category">Cactus Family</p>
          <div class="card">
            <tabs
              centered
              type="neutral"
              tab-nav-wrapper-classes="card-header"
              tab-content-classes="card-body text-center"
              data-background-color="cactus"
            >
              <tab-pane>
                <template slot="label">
                  <i class="now-ui-icons travel_info"></i> Cactus
                </template>
                <p class="text">
                  A cactus is a kind of a plant adapted to hot, dry climates. Plants which
                  live this kind of life-style are called xerophytes. Most are succulents,
                  which store water.
                  <b
                    >Cacti are members of the plant family Cactaceae, in the order
                    Caryophyllales.</b
                  >
                  There are about 127 genera, with over 1750 known species.
                </p>
                <div class="row">
                  <div class="col-md-10 ml-auto col-xl-6 mr-auto">
                    <n-button type="primary" round>
                      <i class="now-ui-icons emoticons_satisfied"></i> Like
                    </n-button>
                    <n-button type="primary" round>
                      <i class="now-ui-icons ui-1_simple-remove"></i> Dislike
                    </n-button>
                  </div>
                </div>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="now-ui-icons ui-2_favourite-28"></i> Old Lady
                </template>
                <p class="text">
                  The old lady cactus is a type of pincushion cactus in the mammillaria
                  family, which has 250 species. It has hairs and spines and is known for
                  its halo of tiny pink or purple flowers that bloom in spring. The old
                  lady cactus should be planted in a sandy potting mix and watered every
                  other week.
                </p>
                <div class="row">
                  <div class="col-md-10 ml-auto col-xl-6 mr-auto">
                    <n-button type="primary" round>
                      <i class="now-ui-icons emoticons_satisfied"></i> Like
                    </n-button>
                    <n-button type="primary" round>
                      <i class="now-ui-icons ui-1_simple-remove"></i> Dislike
                    </n-button>
                  </div>
                </div>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="now-ui-icons objects_diamond"></i> Star
                </template>
                <p class="text">
                  Also known as sea urchin cactus or sand dollar cactus, the star cactus
                  is identified by its round body that’s sectioned into eight slices. It
                  is covered with white hairs and tiny white dots. In the spring it blooms
                  a yellow flower. The star cactus only grows two to six inches in
                  diameter, making it an ideal house plant.
                </p>
                <div class="row">
                  <div class="col-md-10 ml-auto col-xl-6 mr-auto">
                    <n-button type="primary" round>
                      <i class="now-ui-icons emoticons_satisfied"></i> Like
                    </n-button>
                    <n-button type="primary" round>
                      <i class="now-ui-icons ui-1_simple-remove"></i> Dislike
                    </n-button>
                  </div>
                </div>
              </tab-pane>
            </tabs>
          </div>
        </div>
        <div class="col-md-9 ml-auto col-xl-5 mr-auto">
          <p class="category">Family Photo</p>
          <div class="card">
            <img v-lazy="'img/cactus_1.png'" class="rounded-circle" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Tabs, TabPane, Button } from "@/components";
export default {
  components: {
    Tabs,
    TabPane,
    [Button.name]: Button,
  },
};
</script>
<style>
.tab-content.tab-content-padding {
  padding: 20px;
}
.text {
  padding: 35px;
}
</style>
