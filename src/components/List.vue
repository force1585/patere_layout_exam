<template>
  <div class="main">
    <div class="mainSide">List:side bar</div>
  </div>
</template>

<script>
export default {
  name: "List",
};
</script>

<style scoped>
.mainSide {
  position: absolute;
  width: 300px;
  z-index: 10;
  top: 55px;
  left: 0;
  bottom: 55px;
  overflow-x: hidden;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  -ms-overflow-style: none;
  border: 1px solid #000;
}
</style>
