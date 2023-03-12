# chatGPT-wx
关于由openAI公司发布的大型预训练语言模型chatGPT3.5接入微信小程序

项目演示地址：vx小程序：智能AI聊天工具

<a href='https://postimg.cc/Z9mhW6VT' target='_blank'><img src='https://i.postimg.cc/Z9mhW6VT/Wechat-IMG548.jpg' border='0' alt='Wechat-IMG548'/></a>

技术爱好者交流群：

<a href='https://postimg.cc/nCskD5Pk' target='_blank'><img src='https://i.postimg.cc/nCskD5Pk/Wechat-IMG724.jpg' border='0' alt='Wechat-IMG724'/></a>


需求定制联系： 微信：youjunqifei

<a href='https://postimg.cc/6TPVtcpG' target='_blank'><img src='https://i.postimg.cc/6TPVtcpG/Wechat-IMG550.jpg' border='0' alt='Wechat-IMG550'/></a>

--------------------------------------------------------------------
api说明
chats1
用的官方api3.5，需要api key100 个轮播速度飞起

chats2
用的反代理，调用官网gpt3.5接口，需要accessToken，accessToken获取地址 https://chat.openai.com/api/auth/session

官网用的EventSource，小程序不支持EventSource，只能接口一次性返回后截取答案

