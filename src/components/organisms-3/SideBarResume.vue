<template>
  <aside class="sidebar">
    <img class="sidebar__menu-icon" src="../../assets/menu-icon.svg" alt="" />
    <SideBarResumeItems />
  </aside>
</template>

<script>
import SideBarResumeItems from "../atoms-1/SideBarResumeItems.vue";

export default {
  name: "SideBarResume",
  components: { SideBarResumeItems },
};
</script>

<style scoped lang="scss">
.sidebar {
  height: 100vh;
  padding: 28px 0;

  display: flex;
  flex-direction: column;
  align-items: center;

  &__menu-icon {
    width: 20px;
    margin-bottom: 20px;
  }
}
</style>
