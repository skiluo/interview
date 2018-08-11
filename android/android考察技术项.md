# Android开发面试技术考察项

## 主要考察方面

Android开发知识与系统实现原理、java水平、IT基础知识以及前沿动态的了解。以Android知识的考察为主，可以大致根据Android知识70%，java知识20%，其他10%来进行考察。

## Android 基础
* Android系统基本框架
* 四大组建的功能和生命周期
* Service 和 Activity 交互可以通过哪些方式进行
* Start service与Bind service启动service生命周期上的异同
* BroadcastReceiver的创建方式有几种，有什么异同
* Activity launchMode有哪些，适用于什么场景
* 对 Activity、view以及window的理解
* View的绘制流程、自定义View的实现
* Touch事件的传递流程
* 对 Android消息机制、Handler、Looper的理解
* Android进程间通信都有哪些方式
* Intent的用途和理解
* Android动画的原理
* Xml与自定义实现视图的异同和优缺点
* 如何进行不同屏幕的适配，dp、px、sp是什么意思，如何使用
* MVC，MVP与MVVM的理解
* 对Context的理解

## Android进阶

* Android系统的启动流程，期间做了什么事情
* Android应用的启动流程
* Android中哪些地方容易造成内存泄漏，如何对内存泄漏进行排查
* Android加载图片应该如何处理，如何进行优化
* 对AIDL以及binder的理解
* 什么是anr，有哪些出发方式，如何进行定位和排查
* 如何排查卡顿以及流畅度的问题
* 如何收集app的崩溃信息
* 如何进行jni的调用，如何进行native函数的注册
* Android工程编译流程
* Android有哪些安全机制
* 内存过低时，Android按什么样的策略杀死进程，释放内存
* Android Framework的工作方式和原理，包括AMS，PMS，WMS等
* 了解Android Linear Allocation的限制，方法数的限制；其解决办法；动态加载，MultiDex等，以及带来的新的问题；
* 对动态加载，插件技术，免安装调起技术以及热修复技术等这一类问题的原理和理解；
* 对Android dalvik以及art虚拟机的理解

## Java技术
* 对java集合框架的了解，hashmap，hashtable，arraylist
* 静态成员类，非静态成员类有什么区别，什么是匿名内部类，其在编译时如何实现
* 反射、注解的原理
* 类加载的过程，classloader双亲委派模型的理解
* 线程同步机制，synchronized、wait、sleep、notify等的原理
* java中的四大引用，使用场景
* java虚拟机的子系统构成，gc原理
* Final 关键字的用法、接口、抽象类区别

## IT基础知识
* 主要是设计模式：单例、工厂、适配器、装饰等，以及在Android中的应用
* 七层网络模型
* 线程、进程的理解
* 一些基本算法

## 前沿技术
* 对Android以及互联网前沿动态的关注、如Android新版本的特性、http2.0的推出与特性
* 了解主流开源框架和基本功能，优缺点与原理