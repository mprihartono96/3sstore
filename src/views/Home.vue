<template>
  <div class="home">
    <Header3SStore />
    <Hero3SStore />
    <Banner3SStore />
    <Insta3SStore />
    <Patner3SStore />
    <Footer3SStore />
  </div>
</template>

<script>
// @ is an alias to /src
import Header3SStore from "@/components/Header3SStore.vue";
import Hero3SStore from "@/components/Hero3SStore.vue";
import Banner3SStore from "@/components/Banner3SStore.vue";
import Insta3SStore from "@/components/Insta3SStore.vue";
import Patner3SStore from "@/components/Patner3SStore.vue";
import Footer3SStore from "@/components/Footer3SStore.vue";

export default {
  name: "Home",
  components: {
    Header3SStore,
    Hero3SStore,
    Banner3SStore,
    Insta3SStore,
    Patner3SStore,
    Footer3SStore
  }
};
</script>
