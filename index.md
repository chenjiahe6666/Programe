<view class="container"> 
 
 <view class="login-icon"> 
 <image class="login-img" src="/images/7.jpg"></image> 
 </view> 
 <view class="login-from"> 
 
 <!--账号-->
 <view class="inputView"> 
  <image class="nameImage" src="/images/6.png"></image> 
  <label class="loginLab">账号</label> 
  <input class="inputText" placeholder="请输入账号" bindinput="usernameInput" /> 
  </view>
 </view> 
 </view>
 
<!--密码-->
 <view class="inputView"> 
  <image class="keyImage" src="/images/5.png"></image> 
  <label class="loginLab">密码</label> 
  <input class="inputText" password="true" placeholder="请输入密码" bindinput="passwordInput" /> 
 </view> 

<!--忘记密码--><!--注册-->
 <view class="changepsw" >
  <navigator url="/pages/changepsw/changepsw"><text>忘记密码？</text></navigator>
  <navigator url="/pages/registered/registered"><text>注册</text></navigator>
  </view>
