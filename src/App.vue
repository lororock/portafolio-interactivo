<script setup>
import HeaderMain from './components/HeaderMain.vue';
import MainProfile from './components/MainProfile.vue';
import CompanySlider from './components/CompanySlider.vue';
import PersonalPresentation from './components/PersonalPresentation.vue';
import CvProfile from './components/CvProfile.vue';
import CertifiedStudies from './components/CertifiedStudies.vue';
import ProfilesReferidos from './components/ProfilesReferidos.vue';
import FooterBar from './components/FooterBar.vue';
</script>

<template>
  <div class="bg-gray-900 text-white">
    <HeaderMain />
    <MainProfile />
    <CompanySlider />
    <PersonalPresentation />
    <CvProfile />
    <CertifiedStudies />
    <ProfilesReferidos />
    <FooterBar />
  </div>
</template>

<style>
.bg-custom-bg-image {
  background-image: url('assets/background.webp');
  background-position: center;
  background-size: cover;
  height: 100vh;
}
</style>