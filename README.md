# FIUI.ORG

fiui.org 网站

[www.fiui.org](http://www.fiui.org)

## 设备列表

见devices目录下json

## 时间轴

见timeline下timeline.yaml

## 如何更新

修改后，push到master分支即可。提交更改之前请先在本地预览以确定没有错误。
使用下面的命令来开启一个web服务，然后访问[http://localhost:8001](http://localhost:8001)以在本地预览

### python2

如果本地有python2环境，在项目根目录执行

```shell
$ python -m SimpleHTTPServer 8001
```

### python3

如果本地有python3环境，在项目根目录执行

```shell
python3 -m http.server 8001
```

### php

如果本地有php环境，在项目根目录执行

```bash
$ php -S 0.0.0.0:8001
```

