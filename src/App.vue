<script>
import HeaderComp from './components/HeaderComp.vue';

export default {
  name: "App",
  components: {
    HeaderComp
  }
}
</script>

<template>
  <HeaderComp />
</template>

<style>
.w-60{
  width: 60%;
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
</style>
