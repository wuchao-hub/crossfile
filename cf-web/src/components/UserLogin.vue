<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
        <li>
            用户名：
            <input v-model="strUserName" />
        </li>
    </ul>
    <ul>
        <li>
            密  码：
            <input v-model="strPassWord"/>
        </li>
    </ul>
    <ul>
        <li>
            <input />
        </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '欢迎登录使用CrossFile'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
