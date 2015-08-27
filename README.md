# wx_pay
微信支付-APP支付示例
---
本demo需要开发者配置自己的参数才可以运行起来

首先在Constants.java中设置相关参数,具体请查看该文件注释，同时根据注释修改androidmanifest.xml文件

要保证：包名和开放平台一致，签名和开放平台一致，并且再公众平台做设置，
详情请阅读: http://pay.weixin.qq.com/wiki/doc/api/app.php?chapter=8_5
*注意：此条仅仅适用于android，ios不受签名文件限制*

要保证回调类WXPayEntryActivity.java文件必须位于包名的wxapi目录下，否则会导致无法回调的情况.
*注意：此条仅仅适用于android,ios有固定格式，请参考ios demo*

[App支付开发文档](https://pay.weixin.qq.com/wiki/doc/api/app.php?chapter=8_1)

