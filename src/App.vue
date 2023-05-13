<script>
import HeaderComp from './components/HeaderComp.vue';
import HeroComp from './components/HeroComp.vue';
import FeaturesComp from './components/FeaturesComp.vue';
import QuickstartComp from './components/QuickstartComp.vue';
import BuildtoolsComp from './components/BuildtoolsComp.vue';
import PlansComp from './components/PlansComp.vue';
import FindoutComp from './components/FindoutComp.vue';
import FooterComp from './components/FooterComp.vue';
import ReturOnTopComp from './components/_microComp/ReturOnTopComp.vue';

export default {
  name: "App",
  components: {
    HeaderComp,
    HeroComp,
    FeaturesComp,
    QuickstartComp,
    BuildtoolsComp,
    PlansComp,
    FindoutComp,
    FooterComp,
    ReturOnTopComp
  }
}
</script>

<template>
  <!-- Header -->
  <HeaderComp />
  <!-- MainView -->
  <div class="mainView">
    <HeroComp />
    <FeaturesComp />
    <QuickstartComp />
    <BuildtoolsComp />
    <PlansComp />
    <FindoutComp />
  </div>
  <!-- Footer -->
  <FooterComp />

  <div class="extraComp">
    <ReturOnTopComp />
  </div>
</template>

<style>
.w-70 {
  width: 70%;
  margin: 0 auto;
}

.d-flex {
  display: flex;
}

.flex-d-column {
  flex-direction: column;
}

.align-items-center {
  align-items: center;
}

.justify-c-center {
  justify-content: center;
}

.justify-c-between {
  justify-content: space-between;
}

.justify-c-around {
  justify-content: space-around;
}

.text-align-center {
  text-align: center;
}

.height-100 {
  height: 100%;
}

.mainView {
  position: relative;
  z-index: 5;
  width: 100%;
}

.highlight {
  color: #2F55D4;
}

.highlight_red {
  color: #DB3E51;
}
</style>
