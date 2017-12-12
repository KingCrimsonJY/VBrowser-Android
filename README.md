# VBrowser-Android
全网视频嗅探缓存APP

简介
---
  一款用于全网视频嗅探、缓存及播放的APP，方便追剧党、出差党随时随地观看缓存好的视频。超强的视频嗅探能力，多线程急速下载。

主要功能
---
  1.网页中包含的主流格式的流媒体视频的嗅探(M3U8,MP4等)  
  2.主流格式的流媒体视频的缓存(M3U8及传统单文件视频(如MP4, avi))  
  3.已缓存的视频播放(目前调用外部播放器，如MXPlayer)

特色
---
  1.基于Chrome内核的浏览器核心([CrossWalk][1]);  
  2.M3U8嗅探, 缓存, 播放;  
  3.强力的视频嗅探功能;   
  4.多线程下载(M3U8 & NormalVideoFile)

设备需求
---
  架构: arm、x86  
  Android 4.1+

如何运行
---
  方法1:下载[releases][2]下最新版本对应架构的APK文件，并安装至设备  
  方法2:下载源码，编译获得APK，并安装至设备

写在后面
---
  1.该项目纯属兴趣之作，欢迎一起完善;  
  2.优先开发Android版本主要为了验证可行性(吐槽一下苹果的99$保护费，自己写APP都不能自娱自乐，差评);  
  3.如有无法嗅探的情况, 请在issue中表明：设备型号、Android版本、视频所在网页Url;  
  4.长按嗅探列表可以清除角标和已嗅探出的视频列表;  
  5.目前的嗅探策略为激进型，不会放过任何可疑Url，~~因此也会稍微影响页面的加载速度~~(已优化)

请我...喝杯咖啡?
---
![donationImg](https://raw.githubusercontent.com/xm0625/tool.github.io/master/Donation.png)

讨论
---
  [V2EX][3]

License
---
  GPLv2.

  [1]: https://crosswalk-project.org/
  [2]: https://github.com/xm0625/VBrowser-Android/releases
  [3]: https://www.v2ex.com/t/412760
