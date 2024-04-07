<template>
  <div class="leftSide">
    <SideBar />
  </div>
  <div class="rightSide">

  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import SideBar from "@/components/SideBar.vue"; // @ is an alias to /src

@Options({
  components: {
    SideBar,
  },
})
export default class HomeView extends Vue {}
</script>

<style scoped lang="scss">
.leftSide{
  position: fixed;
  left: 0;
  top: 0;


}
</style>