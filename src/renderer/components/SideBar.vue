<template>
  <div class="wrapper clearfix">
    <button type="button" class="btn btn-secondary float-left">Example Button floated left</button>
    <button type="button" class="btn btn-secondary float-right">Example Button floated right</button>
  </div>
</template>

<script>
  export default {
    name: 'SideBar'
  }
</script>

<style scoped>
  .wrapper {
    height: 100%;
    overflow-y: auto;
  }
</style>
