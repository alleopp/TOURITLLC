<template>
  <div id="app">
    <Sidebar/>
  </div>
</template>


<script>
  import Sidebar from './components/Sidebar.vue'

  export default {
    name: 'App',
    components: {
      Sidebar
    }
  }
</script>

<style>
  .header-sidebar {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    width: 100%;
  }
  .h4 {
    display: flex;
    align-items: center;
  }
</style>