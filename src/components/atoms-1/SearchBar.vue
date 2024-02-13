<template>
  <div class="search">
    <input
      class="search__input"
      type="text"
      id="check"
      placeholder="Pesquisar..."
    />
    <img
      class="search__image"
      src="../../assets//icons/search-icon.svg"
      alt=""
    />
  </div>
</template>

<script>
export default {
  name: "SearchBar",
};
</script>

<style scoped lang="scss">
.search {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;

  &__input {
    width: 100%;
    min-width: 400px;
    height: 42px;
    padding-left: 16px;
    border-radius: 25px 0 0 25px;
    border: 1px solid #2c3133;
    background-color: transparent;
    outline: none;
    font-size: 16px;

    &:focus {
      color: #fff;
    }
  }

  &__image {
    width: 30px;
    height: 44px;
    padding: 0 12px;
    border: 1px solid #2c3133;
    margin-left: -1px;
    border-radius: 0 25px 25px 0;
  }
}
</style>
