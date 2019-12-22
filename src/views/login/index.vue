<template>
  <div class="login">
    <!-- 卡片组件 -->
    <el-card class="login-card">
      <div class="title">
        <img src="../../assets/img/logo_index.png" alt />
      </div>
      <!-- 表单容器 -->
      <el-form style="margin-top:30px">
        <!-- 表单域 -->
        <el-form-item>
          <!-- 放置具体组件 ，登录手机号-->
          <el-input placeholder="请输入手机号"></el-input>
          <el-form-item>
            <el-input style="width:65%" placeholder="请输入验证码"></el-input>
            <el-button style="float:right" plain>发送验证码</el-button>
          </el-form-item>
          <el-checkebox>我已阅读并同意用户协议和隐私条款</el-checkebox>
        </el-form-item>
        <el-form-item>
          <el-button type="primary" style="width:100%">登录</el-button>
        </el-form-item>
      </el-form>
    </el-card>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less" scope>
.login {
  background-image: url("../../assets/img/login_bg.jpg");
  background-size: cover;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  .login-card {
    height: 350px;
    width: 440px;
    .title {
      text-align: center;
      img {
        height: 50px;
      }
    }
  }
}
</style>
