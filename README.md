LocalCDN
----
build your onw local cdn to access website fast!

构建自己本地的CDN来提高网站的访问速度

# 已添加的资源列表
- 127.0.0.1 ajax.googleapis.com

# How to use
## 1. 将项目clone下来，并运行
```bash
git clone git@github.com:gefangshuai/LocalCDN.git
cd LocalCDN/build
```
double click `run.bat`

## 2. 修改本地host文件

进到`C:\Windows\System32\drivers\etc`目录下，打开`hosts`文件，将`LocalCDN/build/hosts.txt`中的内容，复制到你自己的hosts文件中

over！

## 3. 刷新dns缓存（非必须，如果发现没起作用，再操作）

```bash
ipconfig /flushdns
```
## 后续
本项目刚起步，所以还不成熟，后续的发展希望越来越多的开源精神的人加进来，提供静态资源，丰富本地cdn，造福更多的人更多的需求！