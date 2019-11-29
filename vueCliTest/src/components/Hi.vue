<template lang="html">
<div>
  <h2>
    {{message}}
    <router-view/>

  </h2>
</div>
</template>

<script>
export default {
  name:'Hi',
  data(){
    return{
      message:'welcome to inner Mongolia！！,,,,,Mongolia！！Mongolia！！Mongolia！！',
      msg:'wangwu改了点东西'
    }
  }
}
</script>

<style lang="css" scoped>

</style>
