# elk-quick
> 快速启动一个单机版的elk,并且启动一个nginx产生日志
1. 访问nginx 产生访问日志
```bash
for i in {1..20};do curl http://YOU-IP:8088;sleep 1;done
```
2. 访问kibana查看日志
```bash
http://YOU-IP:5601
```
test

