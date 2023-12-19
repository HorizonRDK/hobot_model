# hobot_model



## 编译成deb安装包


```
fakeroot dpkg-deb --build hobot-models-basic .
```

## 修改deb安装包版本号

修改`hobot-models-basic/DEBIAN/control`文件中`Version`字段。


## 增/删/改模型文件

更新`hobot-models-basic/opt/hobot/model/x3/basic/`路径下文件。


