#### 近期发现有人使用默认密码恶意扫描程式后台，请检查自己的后台密码是否为默认弱密码。如之前为默认密码没有修改，请第一时间检查自定义矿池中是否出现非自己添加的第三方IP。

#### 當前版本：{BUILD_VERSION}({BUILD_DATE})
#### 最新版本：[V6.3.3_ETHASH(2022-02-09)](https://github.com/mine-Proxy/MinerProxy) 
#### 聯繫我們：[Telegram 討論群組(歡迎向我們提出建議)](https://t.me/+h5eCcxlmHzg3NzA9)、[GitHub](https://github.com/mine-Proxy/MinerProxy)
#### QQ群：893145602
----
#### V1.3.3更新内容：此次版本为小版本更新，可以选择不更新，建议需要CrazyPool的用户或6.3.1/6.3.2版本更新。
- 优化6.3.1/6.3.2版本的内存佔用情况
- 修复ETC内置矿池地址中 2Miners 亚洲节点信息配置错误的问题
- 修复ETC自定义矿池地址无法连接的问题
- 修复6.3.2无法动态修改抽水率的问题
#### 注意：1、由于协议差异, 目前无法实现跨协议抽水, 所以如果设置CrazyPool为归集目标的话需要客户端均使用NiceHash/Stratum2协议。
----
#### 掉綫原因参考表：
- EOF: 客户端主动发出的下綫请求
- i/o timeout: 长时间未收到客户端的提交
- reset bt peer: TCP连接被重置，可能是綫路波动丢包或阻断
