# OnlineJudge 2.0

[![Python](https://img.shields.io/badge/python-3.6.2-blue.svg?style=flat-square)](https://www.python.org/downloads/release/python-362/)
[![Django](https://img.shields.io/badge/django-1.11.4-blue.svg?style=flat-square)](https://www.djangoproject.com/)
[![Django Rest Framework](https://img.shields.io/badge/django_rest_framework-3.4.0-blue.svg?style=flat-square)](http://www.django-rest-framework.org/)
[![Build Status](https://travis-ci.org/QingdaoU/OnlineJudge.svg?branch=master)](https://travis-ci.org/QingdaoU/OnlineJudge)

> #### 基于 Python 和 Vue 的在线评测系统。 [Demo](https://qduoj.com)


## 概览

+ 基于 Docker，真正一键部署
+ 前后端分离，模块化编程，微服务
+ ACM/OI 两种比赛模式、实时/非实时评判 任意选择
+ 丰富的可视化图表，一图胜千言
+ 支持 Template Problem，可以添加函数题甚至填空题
+ 更细致的权限划分，超级管理员和普通管理员各司其职
+ 多语言支持：`C`, `C++`, `Java`, `Python2`, `Python3`，题目可以选择使用的语言
+ Markdown & MathJax 支持
+ 比赛用户IP限制 (CIDR ranges)

主要模块均已开源:

+ 后端(Django): [https://github.com/QingdaoU/OnlineJudge](https://github.com/QingdaoU/OnlineJudge)
+ 前端(Vue): [https://github.com/QingdaoU/OnlineJudgeFE](https://github.com/QingdaoU/OnlineJudgeFE)
+ 判题沙箱(Seccomp): [https://github.com/QingdaoU/Judger](https://github.com/QingdaoU/Judger)
+ 判题服务器(对Judger的封装): [https://github.com/QingdaoU/JudgeServer](https://github.com/QingdaoU/JudgeServer)

## 安装

请根据此进行安装:  [https://github.com/QingdaoU/OnlineJudgeDeploy/tree/2.0](https://github.com/QingdaoU/OnlineJudgeDeploy/tree/2.0)

## 文档

[http://docs.onlinejudge.me/](http://docs.onlinejudge.me/)



Modern browsers(chrome, firefox) 和 Internet Explorer 10+.

## 特别感谢

+ 所有为本项目做出贡献的人
+ [heb1c](https://github.com/hebicheng) 同学为我们提供了很多意见和建议

如果您觉得这个项目还不错，就star一下吧 ：)

## 许可

The [MIT](http://opensource.org/licenses/MIT) License
