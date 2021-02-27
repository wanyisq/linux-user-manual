1. 在fish或者bash终端配置错误环境变量，可以在当前终端输入以下命令临时更改环境变量，再使用正常命令更改环境变量。
```
export PATH=/usr/bin:/usr/sbin:/bin:/sbin:/usr/X11R6/bin
```

2. fish终端配置环境变量的方法是，编辑
```
sudo vim ~/.config/fish/config.fish
```
在config.fish文件内输入
```
set PATH （你想要加入的路径） $PATH
```

3. 解压zip格式文件夹乱码时可以使用如下命令即可
```
unzip -O GBK xxx.zip
```
或
```
unzip -O GB18030 xxx.zip
```
