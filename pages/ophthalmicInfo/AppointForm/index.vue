<template>
  <div>
    <Header />
    <Navbar />

    <MainBanner />
    <AppointForm />

    <Footer />
  </div>
</template>

<script>
import Header from "@/components/commom/head/Header.vue";
import Navbar from "@/components/commom/head/Navbar.vue";
import Footer from "@/components/commom/foot/Footer.vue";

import MainBanner from "@/components/content/ophthalmicInfo/serveYyue/MainBanner.vue";
import AppointForm from "@/components/content/ophthalmicInfo/serveYyue/AppointForm/appointFrom.vue";

export default {
  components: { Header, Navbar, Footer, MainBanner, AppointForm },
};
</script>

<style lang="scss" scoped>
.section.vedio_box {
  margin-top: 0;
}
</style>
