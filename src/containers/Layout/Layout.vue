<template>
  <div class="layout">
      <router-view></router-view>
 </div>
</template>

<script>
export default {
  name: 'Layout',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../../assets/style/base.scss";
</style>