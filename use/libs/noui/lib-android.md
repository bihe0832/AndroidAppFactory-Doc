# LibAndroid

![LibAndroid](https://img.shields.io/badge/AndroidAppFactory-LibAndroid-brightgreen)
[ ![Github](https://img.shields.io/badge/Github-LibAndroid-brightgreen?style=social) ](https://github.com/bihe0832/AndroidAppFactory/tree/master/LibAndroid)
[ ![Maven Central](https://img.shields.io/maven-central/v/com.bihe0832.android/lib-android) ](https://search.maven.org/artifact/com.bihe0832.android/lib-android)

## 功能简介

一些系统接口，由于 Android 版本的原因不在可以直接使用，直接引入相关源码

## 组件信息

#### 引用仓库

引用仓库可以参考 [组件使用](./../start.md) 中添加依赖的部分

#### 组件使用

```groovy
implementation 'com.bihe0832.android:lib-android:+'
```

## 组件功能

###  AXMLPrinter2 系列：
  
- 对官方工具AXMLPrinter2针对不同api下AndroidMainfest编码不同导致解析异常的优化
    
### SystemProperties：

- 获取 SystemProperties 的 native接口调用

### Process：
  
- 系统的 Process 类
