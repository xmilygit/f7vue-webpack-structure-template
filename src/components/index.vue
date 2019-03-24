<template>
  <f7-page>
    <f7-navbar>
      <f7-nav-left>
        <f7-link>Left Link</f7-link>
      </f7-nav-left>
      <f7-nav-title>My App</f7-nav-title>
      <f7-nav-right>
        <f7-link>Right Link</f7-link>
      </f7-nav-right>
    </f7-navbar>
  </f7-page>
</template>


<script>
export default {
  data() {
    return {};
  },
  async mounted() {
    this.hiddebeginloading();
  },
  //隐藏页面首次加载的loading画面
  methods: {
    hiddebeginloading() {
      document.getElementById("beginloading").style.display = "none";
    }
  }
};
</script>
