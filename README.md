# QuickUFC

1. UFC按键配置: 中文版DCS 改入按键设置,省得需要每一个键去设置.

2.警告灯服务程序: 用来转发DCS警告灯的状态,并发送给QuickUFC. 需要先运行此程序.

3.支持DCS-BIOS协议,只需改动一句代码 DCS-BIOS/BIOSConfig.lua  ,   找到并修改如下 
  BIOS.protocol_io.UDPSender:create({ port = 7777, host = "127.0.0.1" })
  
4.dcs-bios-v0.7.1_QuickUFC.zip 为已经修改好的dcs-bios v0.71的版本
  可以直接复制到 C:\Users\你的主机名\Saved Games\DCS\Scripts中. 
  如果找不到直接把下边复制到地址栏:
  %USERPROFILE %\Saved Games\DCS\Scripts 
  直达位置,直接粘贴.

具体操作功能测试视频可打开浏览器访问

https://www.bilibili.com/video/av36194432

设置按键部分可以看下面视频的相关部分

https://www.bilibili.com/video/av24322238

或是b站搜索[ 奎克质造 ] 关键字搜索视频.
