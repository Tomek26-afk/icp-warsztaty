<template>
  <div class="container mx-auto flex flex-col items-center justify-center gap-16 px-2">
    <calculator/>
    <Header />
  </div>
</template>

<script>
import Header from"./components/Header.vue";
import calculator from"./components/calculator.vue";
export default {
  name: "App",
  components: {
    Header,
    calculator,
  },
};
</script>