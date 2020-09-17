<template>
  <div id="tab_bar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "Tabbar"
}
</script>

<style scoped>

#tab_bar {
  display: flex;
  background-color: #f6f6f6;

  position: fixed;
  z-index: 99;
  left: 0;
  bottom: 0;
  right: 0;
  box-shadow: 0 -1px 1px rgba(100, 100, 100, .1);
}


</style>
