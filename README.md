# Spring Cloud Zipkin Example

### Step01 - 启动zipkin

```
/Users/hyy044101331/java_tools/zipkin
sh startup.sh
```

http://127.0.0.1:9411/zipkin/

### Step02 - 启动zipkin-server[1-4]

```
http://127.0.0.1:8081/zipkin
http://127.0.0.1:8082/zipkin2
http://127.0.0.1:8083/zipkin3
http://127.0.0.1:8084/zipkin4
```

<img src="https://imglf6.nosdn0.126.net/img/dFJTKzkyUDNhSjlsRXJFR3lsVDR1NXZ1a3cxSWs5bVlJZW9jL0lJNE9JL245Qnplc0hLYnVnPT0.png"/>

### Step03 - 发起service调用链请求

http://127.0.0.1:8081/zipkin

<img src="https://imglf3.nosdn0.126.net/img/dFJTKzkyUDNhSjlsRXJFR3lsVDR1OHMzd0pZeFhHUE5hWnA5VkNlN2RZaXlTZ3VkSkI1N3RBPT0.png"/>