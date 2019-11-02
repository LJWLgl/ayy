### 项目介绍
ayy(爱易园)基于微信小程序开发的，服务校园二手交易，目前包含小程序端和后端，前端是基于小程序原生开发，后端使用SpringBoot搭建，主要包含以下功能：
+ 商品信息发布与浏览
+ 社交（话题、评论）
+ 商品搜索
+ 位置定位
+ 图片上传
+ 手机号绑定
+ 计数系统
+ ...

### 组织结构
``` lua
ayy
├── ayy-wx   -- 爱易园小程序端
├── ayy-admin -- 爱易园后台管理系统（还未实现）
└── ayy-backend -- 爱易园小程序端
```

### 效果图如下
![image](http://ayy.ganzhiqiang.wang/xgt-4.png?imageView2/2/w/300/q/100)
![image](http://ayy.ganzhiqiang.wang/xgt-2.png?imageView2/2/w/300/q/100)
![image](http://ayy.ganzhiqiang.wang/xgt-3.png?imageView2/2/w/300/q/100)
![image](http://ayy.ganzhiqiang.wang/xgt-1.png?imageView2/2/w/300/q/100)

### 更新

#### 2019.03.26
- 解决微信getUserInfo策略更新而不能登录问题
- war包用docker部署
#### 2019.11.02
- 支持读本地配置

