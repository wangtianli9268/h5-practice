<template lang="html">
  <div class="msg">
    {{msg}}
  </div>

</template>

<script>
export default {
  data(){
    return{
      msg:'ahahah'
    }
  }
}
</script>

<style lang="css" scoped>
  .msg{
    background-color: red;
    color: purple;
    font-size: 40px;
  }
</style>
