<!--
 * @Description: 页面布局组件
 * @Author: icony/精武陈真
 * @Date: 2019-06-21 11:18:48
 * @LastEditTime: 2019-09-11 10:49:20
 * @LastEditors: icony/精武陈真
 -->
<template>
  <div>
    <page-header/>
    <div class="app-container">
        <router-view></router-view>
    </div>
  </div>
</template>

<script>
import PageHeader from './PageHeader'
export default {
  name: 'Layout',
  components: {
    PageHeader
  }
}
</script>

