* 下载地址：[https://www.getpostman.com/](https://www.getpostman.com/)

登陆需要账号，本人是绑定的谷歌账号，因此需要先配置VPN，可以同步你的文件

* postman的环境配置

当你经常性需要测试本地和服务器的接口，但是host和token信息不一致时，是否需要每次更改host头和token信息呢？现在有个简单方法随机切换你的host头或者其他信息。

1、打开Manage Environments

![环境选择](/assets/import.png)

2、添加新的环境参数

![](/assets/environment.png)

3、调用参数

在环境选项中选中当前的环境，然后调用的时候使用{{xxx}}来调用后面的value。

![](/assets/调用参数.png)

