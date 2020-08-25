<template>
  <div>
    <app-store-grid :data="about" />
  </div>
</template>

<script>
import { mapGetters } from "vuex";
import AppStoreGrid from "~/components/AppStoreGrid.vue";

export default {
  components: {
    AppStoreGrid
  },
  computed: {
    ...mapGetters(["about"])
  }
};
</script>

<style lang="scss" scoped>
</style>