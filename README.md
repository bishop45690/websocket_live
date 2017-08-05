# websocket_live
一个基于Swoole和Websocket的直播间Demo

### 本项目需要Pecl环境支持

## 开始

 1. `pecl install swoole`
 2. `git clone https://github.com/komeiji-satori/websocket_live.git`
 3. `cd websocket_live`
 4. `php live_backend.php`
 5. 直播流推送地址: `http://127.0.0.1/websocket_live/live_push.html`
 6. 直播流播放地址: `http://127.0.0.1/websocket_live/live_receive.html`
 

## 效果

### 使用摄像头
![深度截图_选择区域_20170805170734.png](https://i.loli.net/2017/08/05/59858af412388.png)

### 使用视频文件
![57415Si.png](https://i.loli.net/2017/08/05/5985bccb2f428.png)