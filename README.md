# ShadowSocksR 客户端搭建
目录结构如下
|_ ssr-polipo
|_ ssr-privoxy
|_ Readme.md

## 使用POLIPO作为proxy代理

```
ssr init        #初始化shadowsocksR 和 polipo相关环境
ssr config      #配置ssr的config.json、polipo参数、docker proxy代理、全局代理
ssr start       #启动 ssr 、polipo
ssr stop        #停止 ssr polipo 恢复环境变量
ssr autostart   #自动启动
ssr resetproxy  #重置环境变量
ssr unsetproxy  #恢复环境变量
```
   
## 使用PRIVOXY作为proxy代理
```
ssr help        #帮助命令
ssr install     #安装shadowsocksR和privoxy，下载gfwlist2privoxy工具
ssr uninstall   #卸载shadowsocksR、privoxy，删除环境变量、配置文件
ssr config      #设置shadowsocksR 的config.json、docker proxy、全局代理
ssr start       #启动服务
ssr stop        #停止服务
ssr restart     #重启
ssr test        #测试是否安装成功
ssr log         #查看日志
ssr clean       #清除配置文件

```
执行命令后，需要source /etc/profile 或 source ssr xxx 确保环境变量生效
