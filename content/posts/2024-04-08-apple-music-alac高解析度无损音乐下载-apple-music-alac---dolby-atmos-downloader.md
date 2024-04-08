---
title : "Apple Music Alac高解析度无损音乐下载-Apple Music ALAC / Dolby Atmos Downloader"
date : "2024-04-08T08:22:07+08:00"
draft : false
params:
  author : "优选小报"
slug: "2024-04-08-apple-music-alac高解析度无损音乐下载-apple-music-alac---dolby-atmos-downloader.md"
---

## Apple Music ALAC / Dolby Atmos Downloader

Apple Music ALAC / Dolby Atmos Downloader-Apple Music ALAC / 杜比全景声下载器，是一个Apple
Music Alac高解析度无损音乐下载工具，支持ALAC、杜比及播放列表下载，使用需要 Apple Music
账号，并且需要订阅，切需要一定的动手能力，感兴趣的同学可以研究学习。

## Apple Music Alac高解析度无损音乐下载方法

  1. 使用不具有 Google API 的映像在 Android Studio 上创建虚拟设备。
  2. 安装此版本的Apple Music：国外下载 https://www.apkmirror.com/apk/apple/apple-music/apple-music-3-6-0-beta-release/apple-music-3-6-0-beta-4-android-apk-download/ （国内下载 https://pan.quark.cn/s/09a40dc3fb6d）.您还需要 SAI 来安装它：国外下载 https://f-droid.org/pt_BR/packages/com.aefyr.sai.fdroid/（国内下载 https://pan.quark.cn/s/886534670cba）。
  3. 启动 Apple Music 并登录您的帐户。需要订阅。
  4. 端口转发 10020 TCP: `adb forward tcp:10020 tcp:10020`.
  5. 启动 frida 服务器。
  6. 启动 frida 代理：`frida -U -l agent.js -f com.apple.android.music`.
  7. 开始下载一些专辑：`go run main.go https://music.apple.com/us/album/whenever-you-need-somebody-2022-remaster/1624945511`.
  8. 开始下载单曲：`go run main_select.go https://music.apple.com/us/album/whenever-you-need-somebody-2022-remaster/1624945511`输入数字，以空格分隔。
  9. 开始下载一些播放列表：`go run main.go https://music.apple.com/us/playlist/taylor-swift-essentials/pl.3950454ced8c45a3b0cc693c2a7db97b`或`go run main.go https://music.apple.com/us/playlist/hi-res-lossless-24-bit-192khz/pl.u-MDAWvpjt38370N`。
  10. 对于杜比全景声：`go run main_atmos.go https://music.apple.com/us/album/1989-taylors-version-deluxe/1713845538`.

## Apple Music Alac高解析度无损音乐下载

工具打包：夸克网盘 https://pan.quark.cn/s/7f31c9f7b1e6

GitHub：https://github.com/zhaarey/apple-music-alac-atmos-downloader
https://github.com/zhaarey/apple-music-alac-atmos-downloader

**资源收集于网络，侵权联系我删除||资源过期扫码关注我私信**![](//img7-1.zhekoulieshou.com/mmbiz_jpg/iaHBVewvSIbAjcr9g6TlCXSfiaDqkbzuEzp207hVzPqT4YGQOAazQ1KNHCeACbia5Lzq4Ckwibe48iar1q7lgVP1o3w/640?wx_fmt=jpeg&from=appmsg)


