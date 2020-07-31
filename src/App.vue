<template>
  <div id="app">
    <calendar>
      <template #calendarTitle>
        <span>标题</span>
      </template>
    </calendar>
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
