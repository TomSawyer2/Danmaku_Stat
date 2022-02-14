# Danmaku_Stat

B站直播间弹幕统计、礼物统计，WS数据解密部分来自CSDN等等专栏

运行需要在根目录下配置`db.js`，示例如下：

```js
var mysql = {
  host: "ip",
  port: "port",
  user: "user",
  password: "password",
  database: "database",
};
module.exports = { mysql };
```

同时需要在`web.js`中配置对应的房间号，注意房间号不是叔叔站URL中的号码
