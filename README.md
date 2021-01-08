# 介绍
dyniva是基于acquia公司的lightning发行版开发而来的Drupal发行版。

## 使用
通过如下命令使用。
```
composer create-project davyin/dyniva-project dyniva-project --stability dev  --no-interaction
#cp default.settings.php settings.php
#修改数据库指向
#下载数据库，然后解压：http://www.davyin.com/sites/default/files/dyniva/dyniva-8_9.init.sql.gz
# 导入到数据库
```
## 功能特色
1. 精选的drupal模块
1. 组件化建站
1. 适合国情的后台管理界面
1. 集成常见的应用
1. 内容编辑流程
1. 搜索增强
1. 媒体增强
1. SEO
1. ... ...

## 版本路线规划
|Dyniva|Lightning|Drupal core|layout方案|
|---|---|---|----|
|2.1.x|5.1.x|9.1.x|layout builder|
|2.0.x|5.0.x|9.0.x|layout builder|
|1.3.x|4.1.x|8.8.x, 8.9.x|layout builder|
|1.2.x|4.1.x|8.8.x, 8.9.x|panelizer => layout builder|
|1.1.x|4.1.x|8.8.x, 8.9.x|panelizer|
|1.0.x|3.3.x|8.7.x|panelizer|

[lighting 版本说明](https://github.com/acquia/lightning/wiki/Lightning-3.x-vs-4.x)

## lightning_layout 版本兼容性说明
||8.4.x|8.5.x|8.6.x|8.7.x|8.8.x|
|--|--|--|--|--|--|
|1.x|✅|✅|✅|✅|✅|
|2.x|❌|❌|❌|✅|✅|

# 发行版与layout方案选择
|发行版|layout方案|
|--|--|
|varbase|paragraph => layout builder|
|lightning|panelizer => layout builder|
|thunder|paragraph|
|droopler|paragraph|
