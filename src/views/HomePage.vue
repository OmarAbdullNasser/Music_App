<template>
  <div class="HomePage">
    <div class="MainScreen d-flex">
      <SideBar />
      <Main />
    </div>
  </div>
</template>

<script>
import Main from "@/components/Home/Main.vue";
import SideBar from "@/components/Home/SideBar.vue";

export default {
  name: "HomePage",
  components: {
    SideBar,
    Main,
  },
  setup() {},
};
</script>

<style lang="scss" scoped></style>
