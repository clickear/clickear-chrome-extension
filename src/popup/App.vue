<template>
    <Tabs value="name1">
        <TabPane label="标签一" name="name1">标签一1255的内容</TabPane>
        <TabPane label="标签二" name="name2">标签二的内容</TabPane>
        <TabPane label="标签三" name="name3">标签三的内容</TabPane>
    </Tabs>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'This is popup page !'
    }
  }
}
</script>

<style lang="scss">
html, body {
  width: 600px;
  height: 600px;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
