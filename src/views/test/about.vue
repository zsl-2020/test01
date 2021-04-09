<template>
  <div class="test">
    <div>
      我是路由测试模块!!!
      <el-button type="primary" icon="el-icon-search">搜索</el-button>
    </div>
    <HelloWorld />
  </div>
</template>

<script>
import { HelloWorld } from '@/components'
export default {
  components: {
    HelloWorld
  }
}
</script>

<style></style>
