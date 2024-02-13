<template>
  <div class="home">
    <header>
      <HeaderTemplate />
    </header>

    <aside>
      <SideBarResume />
    </aside>

    <main>
      <h1>conteúdo principal</h1>
    </main>

    <footer>footer</footer>
  </div>
</template>

<script>
import SideBarResume from "@/components/organisms-3/SideBarResume.vue";
import HeaderTemplate from "@/components/templates-4/HeaderTemplate.vue";

// @ is an alias to /src

export default {
  name: "HomeView",
  components: { HeaderTemplate, SideBarResume },
};
</script>

<style scoped lang="scss">
.home {
  padding: 0;
  display: grid;
  grid-template-areas:
    "aside header header"
    "aside content content"
    "footer footer footer";
  grid-template-columns: 7% auto;

  header {
    grid-area: header;
  }

  aside {
    grid-area: aside;
  }

  main {
    grid-area: content;
  }

  footer {
    grid-area: footer;
  }
}
</style>
