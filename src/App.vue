<template>
  <div id="app">
    <calendar/>
  </div>
</template>
<script>
    import calendar from './components/calendar/calendar'
  export default {
        components:{
            calendar
        }
  }
</script>

<style lang="less">
  #app{
    width:500px;
  }
</style>
