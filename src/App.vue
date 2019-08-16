<template>
  <div id="app">
    <leftNav></leftNav>
    <div class="main">
      <router-view/>
    </div>
  </div>
</template>
<script>
import leftNav from '@/components/leftNav'
export default {
  name:'app',
  components:{
    leftNav
  }
}
</script>
<style>
#app{
  font-family: 'avenir',Arial, sans-serif;
  text-align: center;
  color:#2C3E50;
  /* margin-top:60px; */
}
.main{
  float:left;
  width: 95%;
  background-color: #EFF2F7;
  height: 100%;
  overflow: hidden;
}
</style>
