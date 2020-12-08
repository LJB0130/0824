<template>
  <div class="login">
    <div class="con">
      <h2>登录</h2>
      <input type="text" placeholder='请输入账号'/><br />
      <input type="text"  placeholder='请输入密码' /><br />
      <div class="btn"><button>登录</button></div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {};
  },
  methods: {},
  mounted() {},
  computed: {},
  watch: {},
};
</script>
<style>
.login {
  width: 100vw;
  height: 100vh;
  background: linear-gradient(to right, #563443, #303d60);
  overflow: hidden;
  text-align: center;
}
.con {
  width: 300px;
  height: 200px;
  background-color: #fff;
  margin: 100px auto;
  border-radius: 10px;
  padding: 20px;
}
.con input {
  width: 60%;
  height: 25px;
  margin-top: 10px;
  outline: none;
}
.con .btn {
  width: 62%;
  height: 30px;
  margin: 20px auto;
  /* background-color: red; */
}
.con .btn button{
    width: 100%;
    height: 30px;
    background-color: #409Eff;
    color: #fff;
    outline: none;
    border: none;
}
</style>