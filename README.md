（支持流量计费、按时间计费、支付宝付款）

除去lnmp的安装时间，仅需3分钟即可完成。


# 代码部分

##### 要求centos 7 x64

### ss-panel mod魔改版一键脚本
```
yum install screen wget -y &&screen -S ss 
wget -N --no-check-certificate https://raw.githubusercontent.com/mmmwhy/ss-panel-and-ss-py-mu/master/ss-panel-v3-mod.sh && chmod +x ss-panel-v3-mod.sh && bash ss-panel-v3-mod.sh

```
### ss-panel v3一键脚本
```
yum install screen wget -y &&screen -S ss
wget -N --no-check-certificate https://raw.githubusercontent.com/mmmwhy/ss-panel-and-ss-py-mu/master/ss-panel_node.sh && chmod +x ss-panel_node.sh && bash ss-panel_node.sh

```

