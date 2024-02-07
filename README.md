# 个人信息管理系统
## Personal information management system
## 一、软件环境：
![Static Badge](https://img.shields.io/badge/%E7%BC%96%E5%86%99%E7%8E%AF%E5%A2%83-Python-rgb(43%2C124%2C254)?style=plastic&logo=python&logoColor=rgb(255%2C255%2C255)&label=%E7%BC%96%E5%86%99%E7%8E%AF%E5%A2%83&labelColor=rgb(91%2C91%2C91)&color=rgb(44%2C125%2C255)&cacheSeconds=3600)
![Static Badge](https://img.shields.io/badge/%E7%B3%BB%E7%BB%9F-Windows11-rgb(43%2C124%2C254)?style=plastic&logo=windows&logoColor=rgb(255%2C255%2C255)&label=%E7%BC%96%E5%86%99%E7%8E%AF%E5%A2%83&labelColor=rgb(91%2C91%2C91)&color=rgb(7%2C128%2C216)&cacheSeconds=3600)
![Static Badge](https://img.shields.io/badge/%E7%BC%96%E8%BE%91%E5%99%A8-Microsoft%20VS%20Code-rgb(35%2C168%2C242)?style=plastic&logoColor=rgb(255%2C255%2C255)&label=%E7%BC%96%E8%BE%91%E5%99%A8&labelColor=rgb(91%2C91%2C91)&color=rgb(34%2C168%2C242)&cacheSeconds=3600&link=https%3A%2F%2Fcode.visualstudio.com%2Fdownload)

## 二、程序运行流程图：

```mermaid
graph TD;
    启动-->登录;
    启动-->注册;
    启动-->退出;
    登录-->输入用户名;
    注册-->输入新的用户名;
    输入用户名-->输入密码;
    输入密码-->密码或用户名不正确;
    密码或用户名不正确-->登录;
    注册-->输入新的密码;
    输入新的密码-->登录;
    输入密码-->系统主界面;
    系统主界面-->新建个人信息;
    新建个人信息-->输入新的姓名;
    输入新的姓名-->输入新的性别;
    输入新的性别-->输入新的年龄;
    输入新的年龄-->输入新的编号;
    输入新的编号-->显示添加信息;
    显示添加信息-->系统主界面;
    系统主界面-->注册新用户;
    注册新用户-->注册;
    系统主界面-->查看个人信息;
    查看个人信息-->输入all;
    输入all-->所有存储在系统中的个人信息;
    所有存储在系统中的个人信息-->系统主界面;
    查看个人信息-->输入编号;
    输入编号-->单个个人信息;
    单个个人信息-->系统主界面;
```

## 、预设账户和密码：
| 账户      | 密码      |
| :-----------: | :-----------: |
| admin      | 123456       |

## 、如何下载？
- 在仓库中直接下载：
  - 1.打开dist文件夹
  - 下载exe文件
- 单击下列按钮下载：
  - <img alt="Static Badge" src="https://img.shields.io/badge/V1.0-%E7%82%B9%E5%87%BB%E6%AD%A4%E5%A4%84%E4%B8%8B%E8%BD%BD-brightgreen?style=social&logo=download&link=https%3A%2F%2Fo8.cn%2FgrOQ">
