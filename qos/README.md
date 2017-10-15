## QOS 限速脚本

## 说明
解决K3路由器在PPPOE 模式下 qos 无效的问题

## 支持环境
官改root版

## 修改点
修改qos文件中以下配置
我是PPPOE拨号 上传15M 下载94M
配置如下
DEV="eth0"
UPLINK=13000
DOWNLINK=80000

