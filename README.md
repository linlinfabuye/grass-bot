# grass-bot
Automate Grass mining with this Python bot, managing multiple Devices and IP address to ensure 24/7 uptime and maximize earnings. Perfect for those seeking a seamless and efficient way to handle WebSocket connections through SOCKS5 Protocol

请使用python3运行代码，如不会使用的可前往Releases下载编译后的版本

无代码基础请直接使用带界面版本


`pip3 install websockets_proxy`


`pip3 install loguru`


修改main函数中user_id和sock5代理列表

如果不使用代理,请运行no_proxy.py

### user_id获取方法

1.打开链接登录https://app.getgrass.io/dashboard

2.页面按F12打开控制台 输入代码

`localStorage.getItem('userId')`

打印的就是当前用户的user_id


![image](https://github.com/user-attachments/assets/0a4f189b-01af-410d-9de6-140574e2518b)


无代码基础请直接使用Releases带界面版本

![image](https://github.com/user-attachments/assets/ecfb963e-9dd6-4527-a4fc-638f298adeae)
