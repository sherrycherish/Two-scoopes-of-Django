# Two Scoops of Django

## Django 1.8 的最佳实践

--------------------------------------------------------------------------------

# Content

## 1\. 作者的笔记

- ### Daniel Roy GreenFeld 的一些话

- ### Audrey Roy Greenfeld 的一些话

## 2\. 介绍

- ### 关于我们的推荐的说明

- ### 为什么是两勺Django

- ### 在你开始之前

  #### 这本书是为 Django 1.8 和 Python 2.7.x/3.3.3+ 设计的

  #### 每章都是独立的

- ### 本书的惯例

- ### 核心概念

  #### 让它简约愚蠢

  #### 庞大的模型层, 简约的视图层, 愚蠢的模板层

  #### Django 默认项目启动方式

  #### 熟悉 Django 的设计哲学

  #### APP 的12个原则

- ### 我们的写作理念

  #### 提供最好的材料

  #### 站在巨人的肩膀上

  #### 倾听读者的声音和反馈

  #### 出版勘误

## 1 编码风格

- ### 让你的代码具有可读性的重要性

- ### PEP 8

  #### 79个字符的限制

- ### 关于 Import

- ### 使用 直截了当的关联 Imports

- ### 避免使用 Import *

- ### Django 编码风格

  #### 考虑Django编码规范的指导方针

  #### 在命名URLpatterns时使用下划线而不是破折号

  #### 在命名模板模块名的时候使用下划线而不是破折号

- ### JS, HTML, CSS 风格 指南

  #### JS, HTML, CSS 风格 指南

  #### HTML ,CSS 风格指南

- ### 永远不要用IDE编程

- ### 总结

# Django 开发环境的最佳搭建方式

## 2.1 使用同一种数据库

## 2.2 使用pip和Virtualenv

## 2.3 使用pip安装Django和其他的依赖

## 2.4 使用一种版本控制系统

## 2.5 可选择的相似的环境

## 2.6 总结

# 如何设计Django项目

## 3.1 Django 1.8 默认的项目布局

## 3.2 我们推荐的项目布局

### 3.2.1 顶层: 仓库目录

### 3.2.2 第二层: 项目目录

### 3.2.3 第三层: 配置目录

## 3.3 布局样例

## 3.4 使用虚拟环境

## 3.5 Going Beyond Startproject

- 3.5.1 使用 Cookiecutter 生成项目Boilerplate
- 3.5.2 我们最喜爱的项目模板
- 3.5.3一个可选择的模板: Django-kevin
- 3.5.4 其他可选择

  ### 3.6 总结

# Django app设计基础

## 4.1 Django App 设计的黄金法则

### 4.1.1 一个实际的例子

## 4.2 怎样命名App

## 4.3 Django App 设计的黄金法则

## 4.3 当怀疑时,保持小项目

## 4.4 什么模块应该属于一个App

- 4.4.1 常用App模块
- 4.4.2 不常用的App模块

  ### 4.5 总结

# Settings 和 Requirements 文件

## 5.1 避免 Non-versioned 的本地文件

## 5.2 使用多种设置文件

- 5.2.1 一个开发设置样例
- 5.2.2 多重开发配置

  ### 5.3 从代码中分离配置

- 5.3.1 在使用环境私有变量前的警告
- 5.3.2 如何设置本地环境变量
- 5.3.3 如何设置生产环境变量
- 5.3.4 处理丢失的密钥异常

  ### 5.4 什么时候不能使用环境变量

- 5.4.1 使用 JSON 文件
- 5.4.2 使用Config, YAML, XML 文件格式

  ### 5.5 使用多个 Requirements 文件

- 5.5.1 从多个 Requirements 文件安装
- 5.5.2 在平台中使用多个 Requirements 文件 作为一个service (PaaS)

  ### 5.6 在设置中处理文件

  ### 总结

# 6 Model 的最佳实践

## 6.1 基础

- 6.1.1 用多层 Models 打破 Apps
- 6.1.2 注意 Model 继承
- 6.1.3 模型继承的实践: 时间戳 Model
- 6.1.4 数据迁移

  ### 6.2 Django 模型设计

- 6.2.1 开始规范化

##
