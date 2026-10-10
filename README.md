# Scutclient4Newifi3
scutclient newifi3 客户端

使用固件：  
newif3D2-512M Padavan 3.4.3.9-099_24-06-1   
[https://opt.cn2qq.com/padavan/RT-N56UB1-newif3D2-512M_3.4.3.9-099.trx](https://opt.cn2qq.com/padavan/RT-N56UB1-newif3D2-512M_3.4.3.9-099.trx)    

上传到路由器  
```
scp -O ./scutclient admin@192.168.123.1:/opt/bin/scutclient
```  
后台常驻运行 (国际校区参数 -s 192.168.53.229)  
```
/opt/bin/scutclient --username 202920144444 --password PW1234567 -i eth2.2 -s 192.168.53.229  -H lenovo >/dev/null 2>&1 &
```

原项目  
https://github.com/scutclient/scutclient
