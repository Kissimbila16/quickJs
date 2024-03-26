<script>
import FootVue from "../layouts/Foot.vue";
import HeaderVue from "../layouts/Header.vue";
import LayoutVue from "../layouts/Layout.vue";
export default {
  name: "ThemeLayout",
  components: {
    HeaderVue,
    FootVue,
    LayoutVue,
  },
};
</script>

<template>
  <div>
    <HeaderVue />
    <LayoutVue />
    <FootVue />
  </div>
</template>
<style scoped>
template {
  margin-left :0%!important;
  width:90%;
}
</style>
