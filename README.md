#FBI WARMIMNG:api 仅供交流，不要外传！


#目前没有添加权限申请，Android 6.0 以上的手机请手动的在设置里面授权所有申请的权限吧！

![image](https://github.com/AnyLifeZLB/AndroidAppFrameWork/raw/master/4.png)

# 封装干什么
  首先，我反对过度封装；封装的目的是为了减少重复代码，精简清晰化项目结构，方便分工开发维护，Demo里面
只有基本的处理，不含LOG,各种Utils 等等，抽象出基类，控制流程。

# 关于Proguard


# 关于JSBridge 和 Webview 中的拍照问题
  演示Demo中assets 目录内置了index.html 和JSbridge.js 来演示，this.goWebView("file:///android_asset/index.html");


# 应用中使用的lib
  其实大部分的App 最难以做好的模块是Http，http 模块封装的好，做起业务来很方便。
  UX 部分多考虑Material design和动画Material-Animations
  ## 建议必选
  - 数据库 GreenDao3(如果有需要使用数据库，建议使用，配置很简洁了)
  - 过度动画 Material-Animations
  - Http请求 retrofit2
  - 列表数据上拉下拉 官方/springview
  - 图片展示 universalimageloader不再维护了，可选用glide,pissico等
  - 权限管理 XXXXXXXXXXXXXXX
  - 二维码 com.journeyapps:zxing-android-embedded

  ## 可选
  - 视图绑定和监听 butterknife/databing
  - rxjava,rxAndroid,Eventbus 。  Square 的东西都很好用，但是
  - Bugly - Umeng(太庞大了)
  - leakcanary
  - +_)(*&^%$E#W@@!@^%%#$@#$!%&!



# 项目中包含的基本的通用模块
- 混淆压缩打包优化 Proguard　proguard-android-optimize　和 proguard-android 区别 ？
  https://github.com/D-clock/Doc/blob/master/Android/Gradle/4_AndroidStudio%E4%B8%8BProGuard%E6%B7%B7%E6%B7%86%E6%89%93%E5%8C%85.md
- Toolbar 的处理
- Fragment 的懒加载
- 通用的BaseActivity 和BaseFragment的封装（跳转PV打点，事件打点）
- 通用的Lib module 的封装
- Http 的闭环处理
- Proguard 混淆 打包优化
- BaseWebView 的处理（未完善，Android 的坑很多）




