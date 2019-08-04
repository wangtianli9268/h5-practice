<template lang="html">
<div>
  <h2>
    {{message}}-{{$route.params.userName}}-{{$route.params.id}}
  </h2>
</div>
</template>

<script>
export default {
  name:'Hi1',
  data(){
    return{
      message:'I am Hi1 page.......'
    }
  }
}
</script>

<style lang="css" scoped>
</style>
