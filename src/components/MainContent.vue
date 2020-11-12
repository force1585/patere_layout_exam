<template>
  <div class="main">
    <div class="mainContent">MainContent</div>
  </div>
</template>

<script>
export default {
  name: "MainContent",
};
</script>

<style scoped>
.main {
  width: 100%;
  height: calc(100vh - 100px);
  display: flex;
}

.mainContent {
  width: calc(100vw);
  border: 1px solid #000;
}
</style>
