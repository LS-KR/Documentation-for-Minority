
本文档主要说明保护自己隐私安全的一些基本知识.  

# 设备
## 手机
尽量不要使用Android, 特别是国内厂商的手机. 有已知后门.  
如果可以的话, 使用iphone, 但也要分辨是否来自国内. 如果是, 则避免使用.  

## 电脑
如果有技术能力的话, 使用Linux. 注意: 不要使用Ubuntu和Deepin, 它们的安全性不足.  
如果经济能承受的话, 使用macOS.  
如果两点均不满足, 则使用Windows. Windows的维护和软件将于下文详细介绍.  

## 服务器
必须使用Linux. 在此建议使用Debian 10.  
如果需要自建代理, 则很有可能会用到服务器. 服务器的隐私保护将于下文详细介绍.  

# 必备技能
## 科学上网
当然, 既然你能看见这个文档, 就说明你已经掌握了科学上网的基本技能.  
在此要求的是:  
1. 尽量不要用免费的代理, 就算自己经济困难也不要.  
2. 如果可能的话, 可以自己在国外购买/租贷一个服务器作为代理服务器.  
3. 可以使用多层代理, 例如Socks->VLess->Proxy.  

## 搜索引擎
**不要使用百度! 不要使用百度! 不要使用百度!**  

可用的搜索引擎:  
1. [Google](https://www.google.com/)
2. [Wikipedia](https://zh.wikipedia.org)

如果是普通的在国内搜索, 也可以使用Bing(bing.com).  

记住: 搜索引擎并不完全可信.  

## Github
开源项目更为安全, 稳定和灵活.  
很大的可能你现在就在Github上查看这篇文档.  
由于某些原因, Github被GFW屏蔽了.  

# 联系方式
注意: 除非是你**完全信任**的朋友, 否则不要让他人知道你的全部联系方式(包括父母).  
给予他人你的**部分**联系方式需要仔细检查是否为友跨且信任的人.  

## 邮箱
尽量不要使用国内的邮箱. 如果可以的话, 使用加密邮箱.
几个常见的邮箱提供商:  
1. [Google](https://www.google.com/intl/zh-CN/gmail/about/)
2. [ProtonMail](https://protonmail.com)
3. [Tutanota](https://tutanota.com)
4. [Mailfence](https://mailfence.com)
5. [Outlook](https://outlook.live.com/owa/)(建议只用来收发国内邮件)
6. [CTemplar](https://ctemplar.com)

除了Gmail和Outlook之外都没听说过? 正常, 毕竟都是加密邮箱且大多数都面向少数群体.  

## 手机号
作为一个及其敏感的联系方式, 除非必要, 否则不要告诉任何人你的手机号.  
如果可能, 请使用+852的手机号.  

## Telegram
Telegram的注册需要手机号, 因此, 使用Telegram联系需要注意.  
请注意: Telegram加好友时会显示手机号, 因此尽量不要使用Telegram的"添加联系人"功能, 并设置"不允许任何人查看你的手机号码".  

## QQ
不要在Windows电脑上直接使用腾讯自家提供的QQ!  
如果需要的话, 可以使用`Icalingua`或`Icalingua++`(https://github.com/Icalingua-plus-plus/Icalingua-plus-plus);  
请注意: **不要传播Icalingua++** [应凌莞(Clansty, Icalingua原开发者)要求]

## 微信
不要使用微信

## Twitter
Twitter可以使用邮箱注册.  
当然, 你很有可能是从Twitter上看到的本文. 如果是这样, 请立即检查你是否将你的手机号链接到了Twitter上.  
如果是, 请立即取消链接.  

Twitter上有大量的应用程序, 这些应用程序不是可信的(除非由你本人开发). 如果你不确定你链接了哪些应用程序, 请立即检查, 并取消链接.  

## Matrix
Matrix是一个开放的聊天工具, 可以使用邮箱注册.  
因此, Matrix并不是一个完全可信的聊天工具.  
但是在一些特殊情况下(如Telegram出现错误), 你可以使用Matrix.  

一个较常见的Matrix: [app.element.io](https://app.element.io/).

## Hack-Chat
Hack-Chat是一个即时的聊天室, 免注册, 但不会保存你的聊天记录.  
网址: [hack.chat](https://hack.chat/).  
作者的Hack-Chat聊天室: [hack.chat/?Elihuso](https://hack.chat/?Elihuso).   

# 设备安全
## 密码
请在几乎所有设备上均设置一个或多个密码, 且不要在所有设备上使用同一个密码.  
一个优秀的密码应该包含大小写字母, 数字, 特殊字符, 并且长度至少为8位.  

将密码存储在本地或写在密码本上是个糟糕的做法.  

## Bitlocker
Bitlocker是一个安全的设备安全解锁工具.  
它有效防止了绕过操作系统的设备内文件提取和攻击.  
但请注意, 如果你忘记了Bitlocker密码, 你的设备将无法解锁, 你的文件将永久丢失.  
  
  
  
除此以外, 在离开设备时应记住锁定你的设备.  
Windows端设备锁定快捷键为`Win+L`, 也可以使用`Ctrl+Alt+Del`然后选择`锁定`.  
macOS端设备锁定快捷键为`Cmd+Ctrl+Q`.  

# 软件
由于macOS和Linux的权限管理, 在此处主要探讨Windows端的软件.  

## 浏览器
**不要使用国内的浏览器!**  

建议的浏览器:
- [Google Chrome](https://www.google.com/chrome/browser/desktop/)
- [Firefox](https://www.mozilla.org/en-US/firefox/new/)
- [Safari](https://www.apple.com/safari/)
- [Opera](https://www.opera.com/zh-cn)

以上网站均需要科学上网  

如果有技术能力的话, 也可以使用Konqueror等小众浏览器.  

## 安全软件
不要使用360等安全软件.  

建议的安全软件:
- [火绒安全软件](https://www.huorong.cn/)
- [Avira](https://www.avira.com/)

如果你在使用Windows 10或更新的Windows, 可以使用[Windows Defender](https://docs.microsoft.com/en-us/mem/intune/user-help/turn-on-defender-windows)  

## 办公软件
不要使用WPS, 有已知后门.  

建议的办公软件:  
- [Microsoft Office](https://www.microsoft.com/zh-cn/office/)
- [LibreOffice](https://www.libreoffice.org/)
- [OpenOffice](https://www.openoffice.org/)

# 维护
## Windows
- 定期进行病毒扫描, 并且使用系统更新.
- 不要使用盗版系统和软件.
- **不要使用那些所谓的"定制系统"**.

***记住: 稳定是最重要的.***

Windows的安全性较低, 因此尽量少在Windows上使用风险较大的软件; 同时, 尽量避免将Windows电脑暴露在公网中.  

## 服务器
- 关注CVE漏洞通报.
- 及时更新系统.(如使用`apt upgrade`)
- 关闭不必要的端口.
- 善用ssh和tmux.

除此以外, 如果服务器同时运行网站服务, 则建议使用CDN代理(如Cloudflare).  

**防范渗透攻击**

# 其他
不要安装国家反诈中心(其实就是后门软件).  
尽量不要暴露行踪轨迹.  

# About
本文是在1h内完成的, 如果你有什么想法, 欢迎在issue中提出.  
如果有什么改进, 欢迎Pr.  
如果你不会用Github, 也可以发送邮件到[Elihuso@outlook.com](mailto:Elihuso@outlook.com).
