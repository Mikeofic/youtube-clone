<template>
  <header class="main-header">
    <SiteLogo />
    <SearchBar />
    <HeaderRightItems />
  </header>
</template>

<script>
import HeaderRightItems from "../organisms-3/HeaderRightItems.vue";
import SearchBar from "../atoms-1/SearchBar.vue";
import SiteLogo from "../atoms-1/SiteLogo.vue";

export default {
  name: "HeaderTemplate",
  components: { HeaderRightItems, SearchBar, SiteLogo },
};
</script>

<style scoped lang="scss">
.main-header {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;

  background-color: #0f0f0f;

  padding: 0 16px;
}
</style>
