# LTSignIn
需要在python3  
联通自动签到领金币。
登录方面暂时没做研究加密算算法，所以应用请求数据fidder分析。  
此任务运行在树莓派上使用crontab 定期自动运行。进行联通手机app上的签到领金币功能。每天运行两次，因为有时候服务器会维护导致签到失败。   
fidder使用要点：由于联通请求使用的https ，fidder需要生成根证书，然后在android模拟器中导入到根证书。fidder即可解密https请求内容。
