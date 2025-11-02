# 前言

欢迎来到培训机构客户管理系统项目的Gitee页面。本项目是基于SSM（Spring、Spring MVC、MyBatis）框架，结合微信小程序、Uniapp等前端技术开发的培训机构客户管理系统。以下将为您详细介绍本项目的相关内容。

## 内容介绍

本项目旨在帮助培训机构实现客户信息的有效管理，提高业务处理效率。系统主要包括以下功能模块：客户信息管理、课程管理、订单管理、数据统计分析等。通过使用本系统，培训机构可以方便地管理客户资料，快速查询和统计客户信息，提高客户满意度，从而促进业务发展。

## 技术介绍

### 语言：Java

### 使用框架：
- Spring
- Spring MVC
- MyBatis
- 微信小程序

### 前端技术：
- JavaScript（JS）
- Vue
- CSS3
- Uniapp

### 开发工具：
- IDEA/Eclipse
- Uniapp

### 数据库：
- MySQL 5.7/8.0

### 数据库管理工具：
- phpstudy/Navicat

### JDK版本：
- jdk1.8

### Maven：
- apache-maven 3.8.1-bin

### 前端环境：
- Node.Js 12\14\16

## 核心代码

以下是一段关于客户信息查询的核心代码：

```java
// CustomerMapper.xml
<select id="queryCustomerList" resultType="com.trainingsystem.entity.Customer">
    SELECT * FROM customer WHERE customer_name LIKE CONCAT('%', #{customerName}, '%')
    LIMIT #{start}, #{pageSize}
</select>

// CustomerService.java
public List<Customer> queryCustomerList(String customerName, int start, int pageSize) {
    return customerMapper.queryCustomerList(customerName, start, pageSize);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/327761/12/19605/135635/68c4d83cF177b938e/e0b2170cb3b361f3.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/339898/30/10253/15668/68c4d814Ffdd5d89f/7920e5a33984c65f.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/323512/20/19411/43604/68c4d814F0c17e524/fafec9f286e5398c.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/343644/22/2830/44003/68c4d814Fa5f2d605/6065e33d54495976.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/343823/3/2659/11010/68c4d814F14197764/ebd56d0924b1ae4f.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/334153/39/12589/36486/68c4d814F15009835/e5f459a87f9ed576.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348640/18/2786/46777/68c4d815Fcec0cf0f/fbbc693133419812.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/339868/14/10262/28414/68c4d815Fbf66dd87/7814edeba5c6470e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328078/15/19426/22925/68c4d815F4249f706/cbbc3ad6c1e38b9e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/327043/32/19204/81199/68c4d815F2d9bb059/013d59c322824e8f.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
