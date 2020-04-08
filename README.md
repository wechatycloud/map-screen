# map-screen

基于wechaty的消息大屏幕，可以把发给树洞机器人的消息实时展现在地图大屏幕上。

所需步骤：

0、克隆

```
git clone https://github.com/wechatycloud/map-screen.git
```

1、安装
```
cd bot
npm install
```

```
cd ../screen
npm install
```

2、在百度创建一个地图应用 http://lbsyun.baidu.com/apiconsole/key/create

3、在bot的配置文件conf.js中设置MQTT

4、在map的配置文件conf.js中设置MQTT及百度地图API key。

5、启动bot

```
cd bot
node bot.js
```

6、启动大屏幕
```
cd screen
node screen.js
```

