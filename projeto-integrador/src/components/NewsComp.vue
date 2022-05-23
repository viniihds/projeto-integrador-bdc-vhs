<script>
import SidenavComp from "@/components/SidenavComp.vue";
import HeaderComp from "@/components/HeaderComp.vue"
import FooterComp from "@/components/FooterComp.vue"
import NewsContent from "@/components/NewsContent.vue"
export default {
  components: { SidenavComp, HeaderComp, FooterComp, NewsContent },
};
</script>
<template>
  <SidenavComp />
  <HeaderComp />
  <NewsContent />
  <FooterComp />
</template>