<template>
  <div id="app">
    <lv-menu-top></lv-menu-top>
    <lv-content></lv-content>
    <lv-menu-bottom></lv-menu-bottom>
  </div>
</template>

<script>
import LvMenuTop from './MenuTop.vue'
import LvMenuBottom from './MenuBottom.vue'
import LvContent from './Content.vue'

export default {
  name: 'app',
  components: {LvMenuTop, LvMenuBottom, LvContent}
}
</script>