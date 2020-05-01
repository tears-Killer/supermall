<template>
  <div id="app">
  <tab-bar></tab-bar>
  </div>
</template>

<script>
import TabBar from './components/tabbar/TabBar'
export default {
  name: "vue",
  props: {},
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components:{
    TabBar
  }
};
</script>

<style scoped>
@import "./assets/css/base.css";
</style>
