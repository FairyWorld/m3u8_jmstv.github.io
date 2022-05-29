# 卷毛鼠公益项目之电视直播源

- [目录](#目录)
- [**JMSIPTV简介**](#jmsiptv仓库简介)
  - [有效性检测](#有效性检测)
  - [播放器推荐](#播放器推荐)
- [**直播源**](#直播源)
  - [**直播源目录导航**](#直播源目录导航)
  - [**卷毛鼠代理直播源**](#卷毛鼠代理直播源)
    - [电视匣Go代理](#电视匣go代理)
    - [卷毛鼠PHP代理](#卷毛鼠php代理)
    - [更新日志](#更新日志)
  - [**卷毛鼠代理直播平台源**](#卷毛鼠代理直播平台源)
    - [使用教程](#使用教程)
    - [更新日志](#更新日志-1)
  - [**卷毛鼠代理youtube源**](#卷毛鼠代理youtube源)
    - [M3U文件](#m3u文件-2)
    - [更新日志](#更新日志-2)
  - [**卷毛鼠自制轮播源**](#卷毛鼠自制轮播源)
    - [M3U文件](#m3u文件-3)
    - [更新日志](#更新日志-3)
  - [**互联网收集直播源**](#互联网收集直播源)
    - [M3U文件](#m3u文件-4)
    - [更新日志](#更新日志-4)
- [**鸣谢**](#鸣谢)  
---
---

# **JMSIPTV简介**


JMSIPTV是卷毛鼠公益项目之一，主要以分享全球IPTV直播源为主，所有电视直播源均收集于互联网并经过精挑细选而成。同时为方便各位观看，卷毛鼠代理了一些其他平台可开放观看的直播节目/频道。JMSIPTV/JMSRadio内含有世界各国电视直播广播频道，因各国文件差异及认知水平不同在收看节目时请理性思考，恪守爱国、敬业、诚信、友善社会主义核心价值观公民个人层面的价值准则。

卷毛鼠公益项目成立于2020年8月30日，已稳定运行将近两年，卷毛鼠公益项目包括：公益流媒体服务（Emby）、公益电视直播与广播服务（IPTV&Radio）您关注卷毛鼠，卷毛鼠关注世界，世界在您身边！

卷毛鼠公益流媒体 Telegram频道：https://t.me/CurlyMouse

卷毛鼠公益IPTV Telegram频道：https://t.me/CurlyMouseIPTV

卷毛鼠公益流媒体 Telegram交流群：https://t.me/Curly_Mouse

卷毛鼠公益IPTV Telegram交流群：https://t.me/Curly_MouseIPTV

---





## 有效性检测
> 有效性检测工具：IPTV Checker.exe
> 
> 卷毛鼠节目源检测Bot：@iptvcheck_bot
>   * Bot需要在卷毛鼠IPTV群中使用，频道有使用教程




---



## 播放工具推荐
> * Windows端：Potplayer、vlc
> 
> * 电视端：Kodi、TiviMate
> 
> * 手机端：Televizo
> 




---
---




# **直播源**
## **直播源目录导航**
* [卷毛鼠代理直播源](#卷毛鼠代理直播源)
* [卷毛鼠代理直播平台源](#卷毛鼠代理直播平台源)
* [卷毛鼠代理youtube源](#卷毛鼠代理youtube源)
* [卷毛鼠自制轮播源](#卷毛鼠自制轮播源)
* [互联网收集直播源](#互联网收集直播源)



---



## **卷毛鼠代理直播源**
卷毛鼠通过各种程序或项目代理的电视直播源。代理亦可理解为转发的含义，因部分公开的电视直播受限于固定的播放环境，通过代理即可重新定义直播源体现形式，将各种有验证的动态的链接固定为单一的静态链接，方便大家观看。


![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.05.28-brightgreen?style=for-the-badge)


### 电视匣Go代理


通过cloudflare workers代理出的电视匣源，适用任何播放器，因基于cloudflare workers代理，每天只有10w请求，如发现不能播放，说明请求已用光，等待第二天恢复即可。

> https://raw.githubusercontent.com/JMSTV/iptv/main/JMSTV-CFW.m3u

通过vps代理出的电视匣源，适用任何播放器，无任何请求限制，随用随播！

> https://raw.githubusercontent.com/JMSTV/iptv/main/JMSTV-VPS.m3u

### 卷毛鼠PHP代理

卷毛鼠通过PHP代码代理出的电视源，适用任何播放器，因全国运营商网络环境复杂，部分频道播放有可能卡顿，请自行筛选出最快的源使用。因为频道涵盖央视、卫视和各地市县频道，所以本M3U源文件未匹配和添加电视台台标LOGO，需要的可自行匹配添加！同时欢迎各位网友和电视机爱好者们提供台标，谢谢！

节目源当前频道数：666

> https://raw.githubusercontent.com/JMSTV/iptv/main/JMSTV-PHP.m3u

### 更新日志
> **2022.05.28**：电视匣代理源代码已更新，代理源已恢复正常；新增一套PHP代理直播源。
> 
> **2022.05.27**：电视匣官方更换了key数组，代理中key数组失效，项目作者正在咕咕代码，敬请期待~~
> 
> **2022.05.26**：添加两套不同类型的代理源，节目源已套用CloudFlareCDN，如播放卡顿请挂代理观看。
> 


---



## **卷毛鼠代理直播平台源**

卷毛鼠基于Golang语言做的一套国内知名直播平台代理系统，实现重定向访问虎牙、斗鱼、Bilibili直播间M3U8/FLV直播流，将直播平台动态源转换为静态链接，方便在各种终端平台的播放器中直接播放。在原作者(原作者已跑路两年)代码基础上修复了部分错误，提高了代理的性能！更多直播平台将陆续添加。

![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.05.28-brightgreen?style=for-the-badge)

### 使用教程

直播源表现格式：

> 主：https://live.52sf.ga/平台/ID
> 备：https://liveb.52sf.ga/平台/ID
>   * 虎牙=huya；斗鱼=douyu；B站=bilibili

完整直播源举例：

> 主：https://live.52sf.ga/bilibili/10375360
> 备：https://liveb.52sf.ga/bilibili/10375360
> 如果主播下播将无法观看哦~

### 更新日志
> **2022.05.30**：虎牙一起看已修复，斗鱼已修复；增加备份直播代理服务器缓解主服压力。
> 
> **2022.05.28**：虎牙直播间已修复，虎牙一起看修复中。
> 
> **2022.05.27**：B站解析已上线，斗鱼虎牙还在做代码。
> 
---



## **卷毛鼠代理youtube源**

卷毛鼠基于Golang语言做的一套Youtube代理系统，实现重定向访问Youtube直播流无需挂代理，可直接在各种终端平台的播放器中直接播放。目前收录24个频道，如有新的链接可以在issue直接提交，我会更新到代理系统中。

![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.05.29-brightgreen?style=for-the-badge)

### M3U文件

> https://raw.githubusercontent.com/JMSTV/iptv/main/JMSTV-YTB.m3u
> 

### 更新日志
> **2022.05.29**：上线Youtube直播频道代理源，当前收录频道数：24
> 


---



## **卷毛鼠自制轮播源**
卷毛鼠基于Golang语言做的一套自推流轮播系统，可对接全球知名直播平台，也可单独推出轮播节目源。

---



## **互联网收集直播源**
卷毛鼠从互联网以及群友分享的节目源中检测整理的节目源，精简好用。但大街源失效迅速，维护不易，且用且珍惜。

---

## 鸣谢

感谢 [woodongwong](https://github.com/woodongwong) 提供tvfix电视匣代理方案

感谢我飞哥、 [linsongze](https://github.com/linsongze) 提供直播平台和YouTube代理方案，和辛苦修复

最后感谢 [我自己](https://t.me/Curly_Mouse) 提供PHP代理直播源，提供自制轮播源，互联网收集维护大街源
