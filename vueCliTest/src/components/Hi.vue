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
      message:'welcome to inner Mongolia！！,,,,,'
    }
  }
}
</script>

<style lang="css" scoped>

</style>
