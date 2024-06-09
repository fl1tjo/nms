nms官方地址 [node-media-server](https://github.com/illuspas/Node-Media-Server "手机观看MKV视频不错的选择")。

# node-media-server 本地直播简单配置

# OBS设置
## 服务器: rtmp://192.168.31.147:1935/live(本地ip, 端口=> app.js中rtmp端口)
## 推流码: STREAM_NAME

# 播放流
## 常用客户端(iina, vlc, PotPlayer):
## 播放地址: http://192.168.31.147:8000/live/STREAM_NAME.flv

```
npm init -y
npm i node-media-server
node app.js
```