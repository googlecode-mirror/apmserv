APMServ 5.2.0 是一款拥有图形界面的快速搭建Apache 2.2.3、PHP 5.2.0、MySQL 5.0.27＆4.0.26、SQLite、ZendOptimizer、OpenSSL、phpMyAdmin、SQLiteManager，以及 ASP、CGI、Perl网站服务器平台的绿色软件。无需安装，具有灵活的移动性，将其拷贝到其它目录、分区或别的电脑时，均只需点击 APMServ.exe中的启动按钮，即可自动进行相关设置，将Apache和MySQL安装为系统服务并启动。APMServ集合了Apache稳定安全的优点，并拥有跟IIS一样便捷的图形管理界面，同时支持MySQL 5.0 & 4.0两个版本，虚拟主机、虚拟目录、端口更改、SMTP、上传大小限制、自动全局变量、SSL证书制作、缓存性能优化等设置，只需鼠标一点即可完成。

1、注意事项：APMServ程序所在路径不能含有汉字和空格。
2、MySQL默认用户名：root，密码为空
3、MySQL数据库文件存放目录：MySQL5.0\data或MySQL4.0\data
4、网站根目录[HTML,PHP]www\htdocs [ASP](ASP.md)www\asp [CGI,Perl]www\cgi-bin
5、访问本机请用http://127.0.0.1/或https://127.0.0.1/ (如果开启SSL)
6、非默认端口，网址为http://127.0.0.1:端口/或https://127.0.0.1:端口/
7、APMServ集成了以下软件：

Apache 2.2.3 [HTTP服务器]
NetBox 2.8 Build 4128 [HTTP服务器＋ASP脚本解释引擎]
PHP 5.2.0 [PHP脚本解释引擎]
MiniPerl 5.8 [Perl脚本解释器]
MySQL 5.0.27 [MySQL数据库服务器]
MySQL 4.0.26 [MySQL数据库服务器]
SQLite 3.3.8 [SQLite数据库服务器]
phpMyAdmin 2.9.1.1 [MySQL数据库在线管理工具]
SQLiteManager 1.2.0 [SQLite数据库在线管理工具]
ZendOptimizer 3.2.0 [PHP脚本加速引擎]
OpenSSL 0.9.8d [HTTPS(SSL)安全传输协议]

附加组件：
㈠Perl、CGI支持（需下载ActivePerl）：
APMServ 5.2.0 附带的是MiniPerl，可以运行简单的Perl、CGI程序。如果运行复杂的Perl、CGI程序，请下载ActivePerl，安装在 APMServ所在分区根目录下的usr目录中。假如APMServ所在目录为E:\APMServ5.2.0，则将ActivePerl的安装路径选为 E:\usr