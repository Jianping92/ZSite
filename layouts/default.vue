<template>
  <el-row class='default'>
    <el-row class='default-main'>1</el-row>
  </el-row>
</template>

<script>
export default {
  name: 'App',
  components: {},
  data() {
    return {}
  },
  computed: {},
  watch: {},
  created() {
  },
  mounted() {
  },
  methods: {}
}
</script>

<style lang='scss' scoped>
.default {
  position: absolute;
  overflow: hidden;
  overflow-y: auto;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-color: #eee;
  .default-main {
    position: relative;
    padding-top: 70px;
    width: 1280px;
    height: auto;
    margin: 0 auto;
    background-color: burlywood;
  }
}
</style>
