<template>
  <div id="app">
    <Header>
      <template #Logo>
        <Logo />
      </template>
      <template #Search>
        <Search />
      </template>
      <template #SignIn>
        <SignIn />
      </template>
      <template #navigation>
        <Main-menu />
      </template>
    </Header>
    <SubMenu />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Search from "@/components/Search.vue";
import SignIn from "@/components/SignIn.vue";
import MainMenu from "./components/MainMenu.vue";
import SubMenu from "./components/SubMenu.vue";

export default {
  components: {
    Header,
    Search,
    SignIn,
    MainMenu,
    SubMenu,
  },
};
</script>
<style></style>
