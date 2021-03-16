# emqx
部署单节点EMQ  
* form jianshulinux  
# 开始部署  
```yaml
kubectl apply -f emqx-stafuset.yml  
```  
* 默认登录账号密码  
```yaml  
--admin/public  
```
* 服务端口占用说明  
```yaml
18083 MQTT管理员登录页面  
1883 MQTT TCP协议端口  
8883 MQTT/SSL 端口  
8083 MQTT/WebSocket 端口  （也是管理后台访问端口，测试数据收发、账号管理）  
8084 MQTT/WebSocket/SSL 端口  
```
