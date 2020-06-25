# anmpp
android nginx mysql pgsql php-fpm

安装后软件名是 超级主机，请熟知。
如果你的设备不具备 ROOT 权限请不要安装，没有 ROOT 权限将不能正常使用，并且你不能将它安装到 SD卡，你必须把他安装到 内部存储 ，否则软件将不能正常运行（我的 Android 7.1.2，安装到内存卡，频繁报错。）
首次使用需要 ANMPP 的资源包文件，请下载后通过 ANMPP 应用进行安装
对于绝大部分人，都应该下载arm和arm64的资源包（模拟器请下载x86）
arm 和 arm64 的设备请访问以下地址下载资源包：
https://raw.githubusercontent.com/xiaoqidun/anmpp/master/armdev/anmpp.tar.bz2
x86 和 x86_64 的设备请访问以下地址下载资源包：
https://raw.githubusercontent.com/xiaoqidun/anmpp/master/x86dev/anmpp.tar.bz2
网页根目录：/data/data/xiaoqidun.anmpp/files/root/android.wwwroot
Nginx 安装路径：/data/data/xiaoqidun.anmpp/files/root/android.nginx
MySQL 数据库：
账号：root
密码：（空密码）
安装路径：/data/data/xiaoqidun.anmpp/files/root/android.mysql/
PostgreSQL 数据库：
账号：root
密码：root
PHP - FPM：
安装路径：/data/data/xiaoqidun.anmpp/files/root/android.php-fpm
FTP服务器：
账号：root
密码：root
安装路径：/data/data/xiaoqidun.anmpp/files/root/android.bftpd
FTP 的账号密码在 /data/data/xiaoqidun.anmpp/files/root/android.bftpd/etc/bftpd.conf 文件当中，每一行代表一个账号密码，使用以下格式：
username password ftpgroup homeroot
账号名称   账号密码  账号分组 访问路径
默认的网页根路径是，如果有需要修改默认网页根路径，请在 /data/data/xiaoqidun.anmpp/files/root/android.nginx/conf/nginx.conf 中修改：
/data/data/xiaoqidun.anmpp/files/root/android.wwwroot
