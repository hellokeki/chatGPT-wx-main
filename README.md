# chatGPT-wx
关于由openAI公司发布的大型预训练语言模型chatGPT3.5接入微信小程序

项目演示地址：

![5481678034395_.pic.jpg](..%2F..%2F..%2FLibrary%2FContainers%2Fcom.tencent.xinWeChat%2FData%2FLibrary%2FApplication%20Support%2Fcom.tencent.xinWeChat%2F2.0b4.0.9%2F19b8c8c2f260f8262eb16258172182d5%2FMessage%2FMessageTemp%2F9e20f478899dc29eb19741386f9343c8%2FImage%2F5481678034395_.pic.jpg)

技术爱好者交流群：

![5491678038469_.pic.jpg](..%2F..%2F..%2FLibrary%2FContainers%2Fcom.tencent.xinWeChat%2FData%2FLibrary%2FApplication%20Support%2Fcom.tencent.xinWeChat%2F2.0b4.0.9%2F19b8c8c2f260f8262eb16258172182d5%2FMessage%2FMessageTemp%2F9e20f478899dc29eb19741386f9343c8%2FImage%2F5491678038469_.pic.jpg)


需求定制联系：

![5501678038671_.pic.jpg](..%2F..%2F..%2FLibrary%2FContainers%2Fcom.tencent.xinWeChat%2FData%2FLibrary%2FApplication%20Support%2Fcom.tencent.xinWeChat%2F2.0b4.0.9%2F19b8c8c2f260f8262eb16258172182d5%2FMessage%2FMessageTemp%2F9e20f478899dc29eb19741386f9343c8%2FImage%2F5501678038671_.pic.jpg)


--------------------------------------------------------------------
api说明
chats1
用的官方api3.5，需要api key100 个轮播速度飞起

chats2
用的反代理，调用官网gpt3.5接口，需要accessToken，accessToken获取地址 https://chat.openai.com/api/auth/session

官网用的EventSource，小程序不支持EventSource，只能接口一次性返回后截取答案

