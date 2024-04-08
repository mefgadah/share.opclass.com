---
title : "CapsWriter Offline-好用的 PC 端的语音输入 字幕转录工具 无限时长"
date : "2024-03-25T11:30:48+08:00"
draft : false
params:
  author : "优选小报"
slug: "2024-03-25-capswriter-offline-好用的-pc-端的语音输入-字幕转录工具-无限时长.md"
---

## CapsWriter Offline

CapsWriter Offline-CapsWriter 的离线版，一个 PC
端的语音输入、字幕转录工具，完全离线、无限时长、低延迟、高准确率、中英混输、自动阿拉伯数字、自动调整中英间隔，按下键盘上的 大写锁定键，录音开始，当松开
大写锁定键 时，就会识别你的录音，并将识别结果立刻输入，将音视频文件拖动到客户端打开，即可转录生成 srt 字幕。

[![CapsWriter Offline-好用的 PC 端的语音输入 字幕转录工具
无限时长](//img7-1.zhekoulieshou.com/mmbiz_jpg/iaHBVewvSIbAjcr9g6TlCXSfiaDqkbzuEzRY6lD9QMfrNq0RTNnlV4ExPfc1twHL0Ynlx2A7zjDjmFrfaicJojbyg/0)](//img7-1.zhekoulieshou.com/mmbiz_jpg/iaHBVewvSIbAjcr9g6TlCXSfiaDqkbzuEzRY6lD9QMfrNq0RTNnlV4ExPfc1twHL0Ynlx2A7zjDjmFrfaicJojbyg/0)

## CapsWriter Offline特性

  1. 完全离线、无限时长、低延迟、高准确率、中英混输、自动阿拉伯数字、自动调整中英间隔
  2. 热词功能：可以在 `hot-en.txt hot-zh.txt hot-rule.txt` 中添加三种热词，客户端动态载入
  3. 日记功能：默认每次录音识别后，识别结果记录在 `年份/月份/日期.md` ，录音文件保存在 `年份/月份/assets`
  4. 关键词日记：识别结果若以关键词开头，会被记录在 `年份/月份/关键词-日期.md`，关键词在 `keywords.txt` 中定义
  5. 转录功能：将音视频文件拖动到客户端打开，即可转录生成 srt 字幕
  6. 服务端、客户端分离，可以服务多台客户端
  7. 编辑 `config.py` ，可以配置服务端地址、快捷键、录音开关……

## CapsWriter Offline如何使用

对 Windows 端：

  1. 请确保电脑上安装了 Microsoft Visual C++ Redistributable 运行库 https://learn.microsoft.com/zh-cn/cpp/windows/latest-supported-vc-redist
  2. 服务端载入模型所用的 onnxruntime 只能在 Windows 10 及以上版本的系统使用
  3. 服务端载入模型需要系统内存 4G，只能在 64 位系统上使用
  4. 额外打包了 32 位系统可用的客户端，在 Windows 7 及以上版本的系统可用
  5. 模型文件较大，单独打包，解压模型后请放入软件目录的 `models` 文件夹中

其它系统：

  1. 其它系统，可以下载模型、安装依赖后从 Python 源码运行。
  2. 由于我没有 Mac 电脑，无法打包 Mac 版本，只能从源码运行，可能会有诸多问题要解决。（由于系统限制，客户端需要 sudo 启动，且默认快捷键为 `right shift`）

模型说明：

  1. 由于模型文件太大，为了方便更新，单独打包
  2. 解压模型后请放入软件目录的 `models` 文件夹中

## CapsWriter Offline下载地址

下载地址：夸克网盘 https://pan.quark.cn/s/f73449e808b5

下载地址：百度网盘 https://pan.baidu.com/s/1zNHstoWZDJVynCBz2yS9vg 提取码：eu4c

GitHub：https://github.com/HaujetZhao/CapsWriter-Offline
https://github.com/HaujetZhao/CapsWriter-Offline

**资源收集于网络，侵权联系我删除||资源过期扫码关注我私信**![](//img7-1.zhekoulieshou.com/mmbiz_jpg/iaHBVewvSIbAjcr9g6TlCXSfiaDqkbzuEzp207hVzPqT4YGQOAazQ1KNHCeACbia5Lzq4Ckwibe48iar1q7lgVP1o3w/640?wx_fmt=jpeg&from=appmsg)


