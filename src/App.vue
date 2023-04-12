<template>
  <div id="app">
    <navbar />
    <div class="page-content">
      <main-hero />
      <features />
      <opportunities/>
      <payments/>
      <demo />
    </div>
    <!-- <scale />
    <testimonials />

    <faqs/> -->
    <main-footer />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar";
import MainFooter from "@/components/MainFooter";
import MainHero from '@/components/MainHero';
import Features from '@/components/Features';
import Opportunities from '@/components/Opportunities';
import Payments from '@/components/Payments';
import Demo from '@/components/Demo';
export default {
  name: "App",
  components: {
    Navbar,
    MainFooter,
    MainHero,
    Features,
    Opportunities,
    Payments,
    Demo
  },
};
</script>

<style>
@font-face {
  font-family: "Circular";
  src: url("../public/fonts/Circular/CircularStdBold.ttf");
}
#app {
  font-family: "Circular", "Helvetica Neue", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  font-family: "Circular, Helvetica Neue, Helvetica, Arial, sans-serif";
  color: #374151;
  font-weight: normal;
}
/* .btn {
  color: #311b92;
  font-weight: 500 !important;
  font-size: 12px !important;
  line-height: 16px !important;
  box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.05) !important;
  border-radius: 4px !important;
  cursor: 'pointer';
  white-space: nowrap;
  text-transform: none;
  letter-spacing: 0.25px !important;
} */
.btn-white {
  background: #ffffff !important;
  border: 1px solid #d1d5db;
  box-sizing: border-box;
  box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.05);
  border-radius: 6px;
  color: #311b92 !important;
  margin-right: 10px;
}
.btn-lightgreen {
  background: #b5ea00 !important;
  border-color: #b5ea00;
  box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.05);
  color: #311b92 !important;
  border-radius: 4px;
  position: relative;
}
.page-content {
  overflow: hidden;
}
.limegreen-color {
  color: #AAE900;
}
.white-color {
  color: #fff;
}
</style>
