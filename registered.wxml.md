<view class="container"> 
 
 <view class="login-icon"> 
 <image class="login-img" src="/images/7.jpg"></image> 
 </view> 
 <view class="login-from"> 
 <!--手机号-->
 <view class="inputView"> 
  <image class="nameImage" src="/images/6.png"></image> 
  <label class="loginLab">手机号</label> 
  <input class="inputText" placeholder="请输入手机号" bindinput="usernameInput" /> 
 </view> 
 <view class="line"></view> 
 <!--密码-->
 <view class="inputView"> 
  <image class="keyImage" src="/images/5.png"></image> 
  <label class="loginLab">密码</label> 
  <input class="inputText" password="true" placeholder="请输入密码" bindinput="passwordInput" /> 
 </view> 
 <!--按钮-->
 <view class="loginBtnView"> 
  <navigator url="/pages/dosucces/dosucces">
    <button class="loginBtn" type="primary" size="{{primarySize}}" loading="{{loading}}" plain="{{plain}}" disabled="{{disabled}}" bindtap="login">注册</button> 
  </navigator>
 </view> 
 </view> 
</view>
