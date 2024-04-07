<script setup lang="ts">

</script>

<template>
<div class="sidebar">
  <span class="name">
    <img class="logo" src="../../public/assets/logo.svg" alt="logo">
    <span>nomProvisoire</span>
  </span>
</div>
</template>

<style scoped lang="scss">
.sidebar{
  border-top-left-radius: 25px;
  border-bottom-left-radius: 25px;
  padding-top: 5vh;
  width: 25vw;
  height: 100vh;
  background-color: blue;
}

.logo{
  width: 5vh;
  fill: white;
}

.name{
  color: white;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
</style>