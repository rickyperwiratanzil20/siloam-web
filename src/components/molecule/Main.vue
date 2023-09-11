<template>
  <main>
    <!-- Navigasi -->
    <div class="navigation">Beranda / Aplikasi My Siloam</div>

    <LandingMain></LandingMain>
    <AboutMySiloam></AboutMySiloam>
    <Feature></Feature>
    <MySiloam></MySiloam>
    <InformationHospital></InformationHospital>
    <Reservation></Reservation>
    <Access></Access>
    <Covid></Covid>
    <SiloamHospital></SiloamHospital>
    <EndPage></EndPage>
    <PrivacyPolicy></PrivacyPolicy>
    <AdditionalInformation></AdditionalInformation>
  </main>
</template>

<script>
import LandingMain from "../atom/LandingMain.vue";
import AboutMySiloam from "../atom/AboutMySiloam.vue";
import Feature from "../atom/Feature.vue";
import MySiloam from "../atom/MySiloam.vue";
import InformationHospital from "../atom/InformationHospital.vue";
import Reservation from "../atom/Reservation.vue";
import Access from "../atom/Access.vue";
import Covid from "../atom/Covid.vue";
import SiloamHospital from "../atom/SiloamHospital.vue";
import EndPage from "../atom/EndPage.vue";
import PrivacyPolicy from "../atom/PrivacyPolicy.vue";
import AdditionalInformation from "../atom/AdditionalInformation.vue";

export default {
  name: "Main",
  components: {
    LandingMain,
    AboutMySiloam,
    Feature,
    MySiloam,
    InformationHospital,
    Reservation,
    Access,
    Covid,
    SiloamHospital,
    EndPage,
    PrivacyPolicy,
    AdditionalInformation,
  }
};
</script>

<style>
/* navigation */
.navigation {
  margin: 10px;
  margin-top: 100px;
}
</style>
