<template>
  <section class="header-links">
    <img
      class="header-links__icon"
      src="../../assets/icons/camera-icon.svg"
      alt=""
    />
    <img
      class="header-links__icon"
      src="../../assets/icons/notification-icon.svg"
      alt=""
    />
    <img
      class="header-links__channel-logo"
      src="../../assets/channel-logo.jpg"
      alt=""
    />
  </section>
</template>

<script>
export default {
  name: "HeaderRightItems",
};
</script>

<style scoped lang="scss">
.header-links {
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 16px;

  &__channel-logo {
    height: 42px;
    border-radius: 50%;
    cursor: pointer;
  }

  &__icon {
    height: 25px;
    cursor: pointer;
  }
}
</style>
