# LTSignIn
需要在python3  
联通自动签到领金币。换话费啥的。  
登录方面不知道加密算法，所以应用请求数据wireshake网络嗅探的。目前反正好使。  
此任务运行在树莓派上使用crontab 定期自动运行。进行联通手机app上的签到领金币功能。每天运行两次，因为有时候服务器会维护导致签到失败。  
怕不保险手机装个Qpython，点一下就签到了。反正我是老忘。  
~~已失效。~~  
token可以使用android上的抓包精灵抓到。  
token3天后会失效，可以采用dev分支
近期联通更改了app的外网登录限制导致嗅探比较困难和dev分支的功能受限。  
如果手机root了可以使用4g网络登录后提取app中的cookies然后导入到程序中进行签到以及后续自动化。而且这种方法需要用手机作为热点来连接网络。不知有没有其他解决办法。
功能不算完美，如果我的贡献对您有用感谢支持。  
![donate](https://github.com/pbbqdd/zxfbtbutton/raw/master/wechatalipay.png)
