<template>
  <div class="welcome">
    <h2>
      Welcome
    </h2>
    <h3>
      欢迎登录到电商后台管理系统!
    </h3>
    <div class="info">
      <ul>
        <li>
          <a href="https://github.com/liuxi0603" target="_blank">Github</a>
          <span>我的Github</span>
        </li>
      </ul>
    </div>
    <address>一起学前端吧</address>
  </div>
</template>

<script>
export default {
  name: 'Welcome'
}
</script>

<style lang="less" scoped>
.welcome {
  margin: 30px auto 0;
  font-size: 20px;
  text-align: center;
  color: black;
  h3 {
    margin: 50px auto 0;
    font-size: 30px;
  }
  .info {
    margin: 15px 0 10px;
    ul {
      margin: 20px 0 0 150px;
      li {
        margin: 10px 0 50px;
        text-align: left;
        margin: 10px;
        color: black;
        a {
          text-align: center;
          display: inline-block;
          padding: 5px;
          font-size: 18px;
          border: 3px solid pink;
        }
        a:hover {
          color: pink;
          background-color: green;
        }
        span {
          width: 100%;
          margin-left: 10px;
        }
      }
    }
  }
}
</style>
