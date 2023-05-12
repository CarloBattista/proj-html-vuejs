<script>
import HeaderComp from './components/HeaderComp.vue';
import HeroComp from './components/HeroComp.vue';
import FeaturesComp from './components/FeaturesComp.vue';
import QuickstartComp from './components/QuickstartComp.vue';

export default {
  name: "App",
  components: {
    HeaderComp,
    HeroComp,
    FeaturesComp,
    QuickstartComp
  }
}
</script>

<template>
  <HeaderComp />
  <!-- MainView -->
  <div class="mainView">
    <HeroComp />
    <FeaturesComp />
    <QuickstartComp />
  </div>
</template>

<style>
.w-70{
  width: 70%;
  margin: 0 auto;
}

.d-flex{
  display: flex;
}

.flex-d-column{
  flex-direction: column;
}

.align-items-center{
  align-items: center;
}

.justify-c-center{
  justify-content: center;
}

.justify-c-between{
  justify-content: space-between;
}

.justify-c-around{
  justify-content: space-around;
}

.text-align-center{
  text-align: center;
}

.height-100{
  height: 100%;
}

.mainView{
  position: relative;
  z-index: 5;
  width: 100%;
}

.highlight {
    color: #2F55D4;
}
</style>
