<template>
  <div class="option-container">
    <h1>{{ msg }}</h1>
    <el-radio class="radio" v-model="radio" label="1">备选项 (选项 1)</el-radio>
    <el-radio class="radio" v-model="radio" label="2">备选项 (Option 2)</el-radio>
    <el-radio class="radio" v-model="radio" label="3">备选项 (Option 3)</el-radio>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        msg: '欢迎5555555555555555555555 to "resources/js/components/Example.vue"',
        radio: '1'
      }
    }
  }
</script>
<style scoped>
  .option-container {
    padding: 20px 0px;
  }
</style>
