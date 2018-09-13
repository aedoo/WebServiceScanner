## WebServiceScanner

首先检测输入网段常见的Web端口是否开放，之后进行Web服务开放性扫描，并提取title输出。



扫描结果示例：

![](https://raw.githubusercontent.com/aedoo/WebServiceScanner/master/final.png)



内置的Web端口：（可自行添加或者删除）

```
80,81,82,83,84,85,86,97,88,89,90,91,443,5000,5001,7001,8000,8001,8008,8009,8080,8081,8088,8089,8443,8888,9000,9001,9090,10001,10010
```

默认线程数：200（可自行调整）



##### 使用实例：

`python webservicescanner.py 192.168.1.1/24`

##### 或者：

`python webservicescanner.py 192.168.1.1/16`

