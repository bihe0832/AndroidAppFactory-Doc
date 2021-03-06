# LibThread

![LibThread](https://img.shields.io/badge/AndroidAppFactory-LibThread-brightgreen)
[ ![Github](https://img.shields.io/badge/Github-LibThread-brightgreen?style=social) ](https://github.com/bihe0832/AndroidAppFactory/tree/master/LibThread)
[ ![Maven Central](https://img.shields.io/maven-central/v/com.bihe0832.android/lib-thread) ](https://search.maven.org/artifact/com.bihe0832.android/lib-thread)

## 功能简介

一些系统接口，由于 Android 版本的原因不在可以直接使用，直接引入相关源码

## 组件信息

#### 引用仓库

引用仓库可以参考 [组件使用](./../start.md) 中添加依赖的部分

#### 组件使用

```groovy
implementation 'com.bihe0832.android:lib-thread:+'
```

## 组件功能

### ThreadManager

- 提供了快速在新线程（线程池）、主线程立刻或者延时执行的方法

- 提供了不同优先级的HadlerThread，对外暴露Looper
