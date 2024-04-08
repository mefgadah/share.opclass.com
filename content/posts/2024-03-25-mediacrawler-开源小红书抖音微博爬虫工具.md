---
title : "MediaCrawler-开源小红书抖音微博爬虫工具"
date : "2024-03-25T11:10:04+08:00"
draft : false
params:
  author : "优选小报"
slug: "2024-03-25-mediacrawler-开源小红书抖音微博爬虫工具.md"
---

## MediaCrawler是什么

MediaCrawler是一个在线开源的小红书抖音微博爬虫工具，支持目前能抓取小红书、抖音、快手、B站、微博的视频、图片、评论、点赞、转发等信息。工具原理是利用playwright搭桥，保留登录成功后的上下文浏览器环境，通过执行JS表达式获取一些加密参数
通过使用此方式，免去了复现核心加密JS代码，逆向难度大大降低，使用需要一定的技术知识。

## MediaCrawler功能列表

[![MediaCrawler-
开源小红书抖音微博爬虫工具](//img7-1.zhekoulieshou.com/mmbiz_jpg/iaHBVewvSIbAjcr9g6TlCXSfiaDqkbzuEzhdt0p4ticSJu5uFcfxkgzjtLdzSibicm3MVkibTuicdg0ibcH8YZ23aLDyuQ/0)](//img7-1.zhekoulieshou.com/mmbiz_jpg/iaHBVewvSIbAjcr9g6TlCXSfiaDqkbzuEzhdt0p4ticSJu5uFcfxkgzjtLdzSibicm3MVkibTuicdg0ibcH8YZ23aLDyuQ/0)

## MediaCrawler如何使用

### 创建并激活 python 虚拟环境

    
    
    # 进入项目根目录
    cd MediaCrawler
    
    # 创建虚拟环境
    python -m venv venv
    
    # macos & linux 激活虚拟环境
    source venv/bin/activate
    
    # windows 激活虚拟环境
    venv\Scripts\activate
    
    

### 安装依赖库

    
    
    pip3 install -r requirements.txt

### 安装 playwright浏览器驱动

    
    
    playwright install

### 运行爬虫程序

    
    
    # 默认没有开启评论爬取模式，有需要请到配置文件中指定
    # 从配置文件中读取关键词搜索相关的帖子并爬去帖子信息与评论
    python main.py --platform xhs --lt qrcode --type search
    
    # 从配置文件中读取指定的帖子ID列表获取指定帖子的信息与评论信息
    python main.py --platform xhs --lt qrcode --type detail
    
    # 打开对应APP扫二维码登录
      
    # 其他平台爬虫使用示例, 执行下面的命令查看
    python main.py --help

### 数据保存

  * 支持保存到关系型数据库（Mysql、PgSQL等）
  * 支持保存到csv中（data/目录下）
  * 支持保存到json中（data/目录下）

## 开源小红书抖音微博爬虫工具

源码备份：国内网盘 https://pan.quark.cn/s/78c52d8d4368

GitHub：https://github.com/NanmiCoder/MediaCrawler
https://github.com/NanmiCoder/MediaCrawler

**资源收集于网络，侵权联系我删除||资源过期扫码关注我私信**![](//img7-1.zhekoulieshou.com/mmbiz_jpg/iaHBVewvSIbAjcr9g6TlCXSfiaDqkbzuEzp207hVzPqT4YGQOAazQ1KNHCeACbia5Lzq4Ckwibe48iar1q7lgVP1o3w/640?wx_fmt=jpeg&from=appmsg)


