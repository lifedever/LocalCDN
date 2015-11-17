LocalCDN
----
build your onw local cdn to access website fast!

构建自己本地的CDN来提高网站的访问速度

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

