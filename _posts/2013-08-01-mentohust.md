---
layout: post
title:  "mentohust锐捷替代品"
date:   2013-07-23 10:56:15
---
在linux下，用mentohust来登陆锐捷。


安装:mentohust:<a href="https://code.google.com/p/mentohust/">下载</a>


配置:vi /etc/mentohust.conf按照提示填写，其中网卡一项最好不写，因为如果不填写登陆时会有提示选择。下载windows版的锐捷，将其下的8021x.exe和Ｗ32N55.dll拷到/etc/mentohust/下（可能这个文件夹没有，要自己建一个，mkdir /etc/mentohust)这是因为有的服务器要检查服务端完整性。


使用：sudo mentohust -参数


不加参数就参加配置里的打开。其中-h是帮助。


如果想用舍友的帐号来上登录，可以直接修改克降网卡地址。然后修改mentohust.conf里用户信息。在windows下修改网卡地址，锐捷会报与系统网卡地址不同，不过一样不会掉线。


 
