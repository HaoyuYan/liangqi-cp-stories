<template>
  <div id="app" v-cloak class="m-1">
    <div class="card m-1">
      <div class="card-body">
        <builder></builder>
      </div>
    </div>
    <p style="color: gray;">
    <small>
      <strong>温馨提示</strong><br>
      <div class="center">
        <ul>
          <li>你没有van过的船新良♂七版本</li>
          <li>良七没有我帅</li>
          <li>良七没有我帅</li>
        </ul>
      </div>

      <strong>软件声明</strong><br>
      此软件只限用于休闲娱乐，所有故事均为匿名投稿提供。如有雷同，纯属巧合。
      最终解释权归CP短打生成器作者所有。 如有疑问或者发现了bug，请联系作者。<br>
      联系方式：mxhcpstories@yahoo.com<br>
    </small>
    </p>
  </div>
</template>

<script>
import Builder from './components/cp-story-builder/Builder.vue'

export default {
  name: 'app',
  components: {
    Builder
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
div.center {
  margin-left: auto;
  margin-right: auto;
  display: table;
}
ul {
  text-align: left;
}
</style>
