* 下载地址：[https://github.com/MicrosoftArchive/redis/releases](https://github.com/MicrosoftArchive/redis/releases)

参考地址[ ](http://blog.csdn.net/renfufei/article/details/38474435/)[http://blog.csdn.net/renfufei/article/details/38474435/](http://blog.csdn.net/renfufei/article/details/38474435/)

* 选择[**Redis-x64-3.2.100.msi**](https://github.com/MicrosoftArchive/redis/releases/download/win-3.2.100/Redis-x64-3.2.100.msi)下载，完成后安装

将安装的目录C:\Program Files\Redis添加到环境变量中

* 在桌面新建一个start\_redis.bat的文本文档，内容输入

         cd C:\Program Files\redis

         redis-server  redis.windows.conf ` `



