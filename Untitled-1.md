# Android

## 四层架构

- Linux 内核层

- 系统运行库层

- 应用框架层

- 应用层

## 四大组件

- 活动（activity)

- 服务（service）

- 广播接收器（broadcast receiver）

- 内容提供器（content provider）

## app目录

1. bulid     编译时自动生成的文件

2. libs        第三方jar包

3. Android Test   自动化测试

4. Java       java 代码

5. res         资源存放（drawable 图片    mipmap 应用图标      values 字符串，样式，颜色等配置     layout 布局文件）

6. AndroidManifest.xml   配置文件

7. test        自动测试

8. .gitignore      将app目录中指定的目录或文件排除在版本控制之外

9. app.iml  自动生成的文件

10. Build.gradle    app模块的gradle构建脚本

11. proguard-rules.pro   指定项目代码的混淆规则

## Log

- Log.v()  打印琐碎的日志信息

- Log.d()  打印调试信息

- Log.i()   打印重要的数据

- Log.w() 打印警告信息

- Log.e()  打印错误信息

## data标签

- android:scheme   指定数据的协议部分

- android:host         指定数据的主机名部分

- android:port          指定数据的端口部分

- android:path         指定数据的主机名和端口之后的部分

- android:mimiType     指定可以处理的数据类型

## 引用资源的两种方法

<img src="file:///C:/Users/L/AppData/Roaming/marktext/images/2026-03-23-23-34-35-image.png" title="" alt="" width="779">

## 加载布局

<img src="file:///C:/Users/L/AppData/Roaming/marktext/images/2026-03-24-10-05-00-image.png" title="" alt="" width="634">



## 活动状态

- 运行状态（返回栈的栈顶）

- 暂停状态（不再处于栈顶但仍然可见）

- 停止状态（不再处于栈顶并且完全不可见）

- 销毁状态（从返回栈中移除）



## 活动的生存期

- onCreate() 活动第一次创建时被调用

- onStart()    活动由不可见变为可见时调用

- onResume()   活动准备好和用户进行交互时调用

- onPause()    系统准备去启动或恢复另一个活动时调用

- onStop()      活动完全不可见时调用

- onDestory()    活动被销毁之前调用onRestart()活动由停止状态变为运行状态之前调用 
  
  <img src="file:///C:/Users/L/AppData/Roaming/marktext/images/2026-03-25-23-02-53-image.png" title="" alt="" width="411">



## 返回栈

- 一个任务就是一组存放在栈里的活动的集合

- 是一种先进后出的数据结构

- 系统总是显示处于栈顶的活动给用户



## RelativeLayout

- layout_alignParentLeft

- layout_alignParentRright

- layout_alignParentTop

- layout_centerInParent

- layout_alignParentBottom




