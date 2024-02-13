<template>
  <section class="sidebar">
    <nav class="sidebar__item">
      <img src="../../assets/icons/home.svg" alt="" />
      <strong>Início</strong>
    </nav>

    <nav class="sidebar__item">
      <img src="../../assets/icons/shorts.svg" alt="" />
      <strong>Shorts</strong>
    </nav>

    <nav class="sidebar__item">
      <img src="../../assets/icons/subscribed.svg" alt="" />
      <strong>Inscrições</strong>
    </nav>

    <nav class="sidebar__item">
      <img src="../../assets/icons/music.svg" alt="" />
      <strong>Music</strong>
    </nav>

    <nav class="sidebar__item">
      <img src="../../assets/icons/camera-icon.svg" alt="" />
      <strong>Você</strong>
    </nav>

    <nav class="sidebar__item">
      <img src="../../assets/icons/download.svg" alt="" />
      <strong>Downloads</strong>
    </nav>
  </section>
</template>

<script>
export default {
  name: "SideBarResumeItems",
};
</script>

<style scoped lang="scss">
.sidebar {
  &__item {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 4px;

    width: 26px;
    height: 20px;
    border-radius: 18px;

    font-size: 10px;
    color: #f1f1f1;

    cursor: pointer;
  }

  &__item:hover {
    background-color: #ffffff19;
  }
}
</style>
