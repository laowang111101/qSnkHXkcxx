# 江苏省 hotel 可视化分析系统 python509

## 项目概述

本系统实现了对江苏省13市酒店数据的完整采集、清洗、存储及可视化全流程。基于 Python 语言，使用 Django 框架开发，通过 Selenium 技术爬取 Booking 网站数据，并存储于 sqlite 数据库中。利用 Echarts 进行数据的可视化展现。

## 技术栈

- **后端**: Python, Django 框架
- **数据爬取**: Selenium
- **数据库**: sqlite
- **前端可视化**: Echarts

## 功能模块

- 搜索房源
- 酒店分布热力图
- 评论词云图
- 月度分析
- 周度分析
- 收藏酒店

## 系统角色

- 用户：进行酒店搜索、查看分析图表、收藏酒店等操作。

## 运行环境

- Python 环境推荐版本：3.6+
- 需要安装的依赖库：Django, Selenium, sqlite, Echarts

## 部署步骤

1. 安装 Python 环境及依赖库。
2. 导入 sqlite 数据库文件。
3. 运行 Django 项目，完成部署。

## 目录结构

```
project/
│
├── app1/                # Django 应用目录
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   └── ...
│
├── static/              # 静态文件目录
│
├── templates/           # 模板文件目录
│
├── manage.py            # 项目管理脚本
└── ...
```

## 核心亮点

- **全流程自动化处理**: 数据从采集到可视化，全程自动化处理，提高效率。
- **灵活的搜索功能**: 用户可方便地搜索到所需的房源信息。
- **丰富的可视化展示**: 多种可视化图表直观展现数据特点。
- **Django 框架开发**: 基于成熟的 Django 框架，易于维护与扩展。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img13.360buyimg.com/ddimg/jfs/t1/167969/16/52643/66898/68d4de72Fbfe890b0/7c0398498479737e.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/241355/36/30024/76796/68d4de72F671c9fa9/b64a0c06892eb8cf.jpg)
