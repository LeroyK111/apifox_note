# apifox_note

Apifox = Postman + Swagger + Mock + JMeter。
[官网](https://apifox.com)
挺好用的，我就把用法总结了一篇笔记出来。

## 快捷请求
打开个人项目，使用快捷请求。
![](readme.assets/Pasted%20image%2020230818000248.png)
公共地址：get请求
```
https://api.help.bj.cn/apis/nongli/?id=beijing&now=7&T=e
```
![](readme.assets/Pasted%20image%2020230818003327.png)
![](readme.assets/Pasted%20image%2020230818003353.png)
### 撰写api接口文档
点击保存接口，即可生成接口文档。
![](readme.assets/Pasted%20image%2020230818010632.png)
![](readme.assets/Pasted%20image%2020230818010825.png)
到这里一个接口文档已经写好。本地mock也可以直接跑通。
![](readme.assets/Pasted%20image%2020230818011522.png)

## 正式开发环境里的API文档

### 创建正式接口
![](readme.assets/Pasted%20image%2020230818020430.png)
### 构建自己的数据模型

![](readme.assets/Pasted%20image%2020230818020147.png)
![](readme.assets/Pasted%20image%2020230818020944.png)
### 接口文档导出
#### 目录导出。
![](readme.assets/Pasted%20image%2020230818021634.png)
#### 单接口导出
![](readme.assets/Pasted%20image%2020230818021707.png)
## 前端mock
避免前端无数据可用，这里mock则可以根据字段名，字段类型，字段约束自动生成数据。
![](readme.assets/Pasted%20image%2020230818021853.png)

#### 使用自定义随机数据
![](readme.assets/Pasted%20image%2020230818022224.png)
![](readme.assets/Pasted%20image%2020230818022234.png)
####  高级mock
![](readme.assets/Pasted%20image%2020230818022332.png)

## ★API调试
你只要会postman这里就是类似。
![](readme.assets/Pasted%20image%2020230818022659.png)

#### 动态参数
![](readme.assets/Pasted%20image%2020230818023057.png)

#### 全局变量
自设全局变量引用方式。主要是传参和路径。
```
{{ data }}
```
![](readme.assets/Pasted%20image%2020230818023522.png)

#### 全局参数
主要是请求头，cookie等
![](readme.assets/Pasted%20image%2020230818023628.png)

#### 环境
![](readme.assets/Pasted%20image%2020230818023810.png)
#### 表单校验
![](readme.assets/Pasted%20image%2020230818024216.png)

#### 后置操作
前置操作：处理请求值。
后置操作：处理返回值。
![](readme.assets/Pasted%20image%2020230818024420.png)

#### 支持目录级的前置后置操作
![](readme.assets/Pasted%20image%2020230818024515.png)


#### 也支持项目级别的操作
![](readme.assets/Pasted%20image%2020230818024739.png)
#### 接口测试用例
![](readme.assets/Pasted%20image%2020230818025226.png)

## 自动化测试
这里就开始无聊了。毕竟CI/CD工具蛮多的。
![](readme.assets/Pasted%20image%2020230818025653.png)

### 自动导入三方接口
### 项目概览上看。
![](readme.assets/Pasted%20image%2020230818025850.png)
### 项目设置上看
![](readme.assets/Pasted%20image%2020230818025955.png)
### 在线分享
![](readme.assets/Pasted%20image%2020230818030011.png)
也支持云端mock
![](readme.assets/Pasted%20image%2020230818030221.png)
分享接口表给其他人把


