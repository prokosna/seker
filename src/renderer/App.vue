<template>
  <div id="app">
    <div class="container-fluid px-0">
      <div class="row">
        <div class="col-12">
          <top-bar></top-bar>
        </div>
        <div class="col-12">
          <!-- Advanced Search -->
        </div>
        <div class="col-2">
          <side-bar></side-bar>
        </div>
        <div class="col-10">
          <router-view></router-view>
        </div>
      </div>
      <div class="footer">
      </div>
    </div>
  </div>
</template>

<script>
  import TopBar from './components/TopBar'
  import SideBar from './components/SideBar'

  export default {
    name: 'seker',
    components: { TopBar, SideBar }
  }
</script>

<style>
  html body {
    padding: 0;
    margin: 0;
    height: 100%;
    width: 100%;
    /*-webkit-user-select: none;*/
    overflow: hidden;
  }
</style>
