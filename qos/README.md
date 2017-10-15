## QOS 限速脚本
tc + iptables 完成限速

## 说明
解决K3路由器在PPPOE 模式下 qos 无效的问题

仅分流了下载与http普通请求

## BUGs
暂时无法分离http下载

## 支持环境
官改root版

## 修改点
修改qos文件中以下配置

我是PPPOE拨号 上传15M 下载94M

配置如下

DEV="eth0"

UPLINK=13000

DOWNLINK=80000


