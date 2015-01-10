## 项目搭建

1. 本项目是基于 [Yii2 ](https://github.com/yiisoft/yii2) 高级应用模板开发的，参考文档 [高级应用模板](http://yii2.xlbd.net/web/index.php/guide/3.html)。
1. 配置环境的时候你要配置两个虚拟目录，对于前台指定 `frontend/web/` ，访问URL为 `http://www.xxx.com/` (域名自己随便配置)
1. 对于后台指定 `backend/web/` ，访问URL为 `http://admin.xxx.com/` (域名自己随便配置)
1. git clone 一份代码之后要在项目根目录下在终端运行 `php init` 初始化一下。
1. 手动新建一个数据库名为 vfanr，然后更该 `common/config/main-local.php` 里面的 `dbname=vafanr`。
1. 在终端输入命令 `yii migrate` (windows下面可能是 `php yii migrate` 命令)初始化数据。
1. 在终端输入命令 `curl -sS https://getcomposer.org/installer | php` 安装 PHP 的 [Composer](http://docs.phpcomposer.com/download/)。
1. 在终端输入命令 `php composer.phar global require "fxp/composer-asset-plugin:1.0.0-beta3"` 安装 composer-asset-plugin 来管理静态资源文件。


## 文档和手册

1. [Yii2手册](http://book.getyii.com)
2. [中文 Composer 手册](http://docs.phpcomposer.com/)