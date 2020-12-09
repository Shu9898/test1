<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: "TabBar"
  }
</script>

<style scoped>
  #tab-bar {
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    display: flex;
    /*一般tabbar的高度是49px*/
    height: 49px;
    background-color: #f4f4f4;
    box-shadow: 0 -1px 5px rgba(0, 0, 0, .1);
  }
</style>
