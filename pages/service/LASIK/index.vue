<template>
  <div>
    <Header />
    <Navbar />

    <MainBanner />
    <principle />
    <Benefit />
    <suitable />

    <Footer />
    <footers />
  </div>
</template>

<script>
import Header from "@/components/commom/head/Header.vue";
import Navbar from "@/components/commom/head/Navbar.vue";
import Footer from "@/components/commom/foot/Footer.vue";

import MainBanner from "@/components/content/service/LASIK/MainBanner.vue";
import principle from "@/components/content/service/LASIK/principle.vue";
import Benefit from "@/components/content/service/LASIK/Benefit.vue";
import suitable from "@/components/content/service/LASIK/suitable.vue";
import footers from "@/components/commom/foot/footers.vue";

export default {
  components: {
    Header,
    Navbar,
    Footer,
    MainBanner,
    principle,
    Benefit,
    suitable,
    footers,
  },
  head() {
    return {
      title: "LASIK激光矯視 - 香港希瑪微笑矯視中心",
      meta: [
        {
          hid: "description",
          name: "description",
          content:
            "香港希瑪微笑激光矯視中心提供LASIK激光矯視服務，利用激光及飛秒激光，重塑角膜弧度，從而矯正視力。",
        },
        {
          hid: "keywords",
          name: "keywords",
          content:
            "LASIK激光矯視, 激光矯視 價錢, 激光矯視 香港, 視力矯正, 眼睛健康, 激光矯視, 深近視, 眼睛檢查",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.section.vedio_box {
  margin-top: 0;
}
</style>
