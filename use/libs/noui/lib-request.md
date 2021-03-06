# LibRequest

![LibRequest](https://img.shields.io/badge/AndroidAppFactory-LibRequest-brightgreen)
[ ![Github](https://img.shields.io/badge/Github-LibRequest-brightgreen?style=social) ](https://github.com/bihe0832/AndroidAppFactory/tree/master/LibRequest)
[ ![Maven Central](https://img.shields.io/maven-central/v/com.bihe0832.android/lib-request) ](https://search.maven.org/artifact/com.bihe0832.android/lib-request)

## 功能简介

网络请求相关的请求参数处理，URL校验、合并等

## 组件信息

#### 引用仓库

引用仓库可以参考 [组件使用](./../start.md) 中添加依赖的部分

#### 组件使用

```groovy
implementation 'com.bihe0832.android:lib-request:+'
```

## 组件功能

### URLUtils

- 获取去掉参数的url、url中的文件名、url中的指定key值、请求参数合并拼接

- 获取URLEncode的信息（避免出现 `+` 和 `*` 等特殊字符）等

### HTTPRequestUtils

- 根据URL获取网页Title、ContentType、Charset、ContentLength（兼容超2G文件，contentLength 为 -1）