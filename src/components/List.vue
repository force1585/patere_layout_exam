<template>
  <div class="main">
    <div class="sideBar">List:side bar</div>
  </div>
</template>

<script>
export default {
  name: "List",
};
</script>

<style scoped>
.sideBar {
  position: absolute;
  width: 20%;
  z-index: 10;
  top: 50px;
  left: 0;
  bottom: 50px;
  overflow-x: hidden;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  -ms-overflow-style: none;
  border: 1px solid #000;
}
</style>
