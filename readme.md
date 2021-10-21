# easy-api 三方配置

> 适用于内部团队自用

## 前置条件
保证已安装 [easy-api](http://easyyapi.com/documents/installation.html)

## 增加贷款侧配置
打开 Idea 配置，找到 Other & Settings -> EasyApi -> BuildinConfig
添加如下一行，保存应用即可
```bash
properties.additional=https://raw.githubusercontent.com/lifesign/easy-yapi-config/master/custom.config
```

