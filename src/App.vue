<template>
  <f7-app :params="f7params">
    <!-- initial page is specified in routes.js -->
    <f7-view main url="/"></f7-view>
  </f7-app>
</template>

<script>
import routes from './routes.js'
export default {
  data () {
    return {
      f7params:{
        routes,
        name:'f7vue-strueture-example',
        id:'com.mxthink.f7vue-strueture-example',
        theme:'auto'
      }
    }
  }
}
</script>

<style>
</style>