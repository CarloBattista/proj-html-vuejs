<script>
import HeaderComp from './components/HeaderComp.vue';
import HeroComp from './components/HeroComp.vue';

export default {
  name: "App",
  components: {
    HeaderComp,
    HeroComp
  }
}
</script>

<template>
  <HeaderComp />
  <!-- MainView -->
  <div class="mainView">
    <HeroComp />
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

.align-items-center{
  align-items: center;
}

.justify-c-center{
  justify-content: center;
}

.justify-c-between{
  justify-content: space-between;
}

.mainView{
  position: relative;
  z-index: 5;
  width: 100%;
}
</style>
