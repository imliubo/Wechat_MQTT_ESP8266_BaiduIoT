<div align="center">
	<h1>微信智能小管家</h1>
  <img src="https://makingfun.oss-cn-qingdao.aliyuncs.com/Github/Wechat_MQTT_ESP8266_BaiduIoT/index.png" alt="Wechat mini program" width="280" height="497">
</div>

## Wechat MQTT ESP8266 Baidu IoT

这是一个微信小程序通过MQTT控制硬件(ESP8266)的Demo，教你通过微信小程序控制自己的硬件。相关文章在知乎专栏： **[IAMLIUBO的神奇物联网之旅](https://zhuanlan.zhihu.com/imliubo-magic-IoT-Tutorial)** 可以查看。

演示视频地址：[B站-微信小程序控制硬件](https://www.bilibili.com/video/av47917354/)

**iOS版微信无法连接百度天工MQTT服务器，暂时不知道为什么，建议先使用Android版微信测试**

请依次修改图片中标注的地方，如果还没有注册百度天工账号，可以先用这个账号体验，不确保可以使用多长时间，但是微信小程序的Appid一定要换成你自己的，因为不替换没法使用，页面布局可以根据你的需要自己修改，请忽略我的渣布局~

设备端代码：

官方SDK版本：[Wechat_MQTT_BaiduIoT(SDK)](https://github.com/imliubo/makingfunxyz-esp8266/tree/master/makingfunxyz-esp8266-NONOS/14.Wechat_MQTT_BaiduIoT)

Arduino版本：[Wechat_MQTT_BaiduIoT(Arduino)](https://github.com/imliubo/makingfunxyz-esp8266/tree/master/makingfunxyz-esp8266-Arduino/01.Wechat_ESP8266_BaiduIoT)

PS：使用我的百度天工账号体验，一定要记得勾选**不校验合法域名、web-view（业务域名）、TLS 版本以及 HTTPS 证书**，如果不勾选是没法连接百度天工MQTT服务器的。
<div align="center">
	<h3>修改Appid</h3>
  <img src="https://makingfun.oss-cn-qingdao.aliyuncs.com/Github/Wechat_MQTT_ESP8266_BaiduIoT/appid-setting.png" alt="Wechat mini program">
  	<h3>修改百度天工 IoT Hub账号和连接的网址</h3>
  <img src="https://makingfun.oss-cn-qingdao.aliyuncs.com/Github/Wechat_MQTT_ESP8266_BaiduIoT/app-js-setting.png" alt="Wechat mini program">
  	<h3>修改需要订阅的主题</h3>
  <img src="https://makingfun.oss-cn-qingdao.aliyuncs.com/Github/Wechat_MQTT_ESP8266_BaiduIoT/topic-setting.png" alt="Wechat mini program">
</div>

## Thankful:

微信小程序MQTT架构-[爱吃猫粮的鱼](https://github.com/tennessine/miniprogram-mqtt5)
