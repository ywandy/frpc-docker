### frpc的docker镜像

```bash
author: yewei_andy
email: yewei_andy@163.com
```



**封装各种版本的frpc**



#### 使用说明

```bash
docker run -d --net host --restart always -v {你的frpc.ini配置文件}:/frp/frpc.ini oldiy/fprc:版本号
#--net host 使用主机网络，使用主机的端口
#--restart always 退出后自动重启
```

