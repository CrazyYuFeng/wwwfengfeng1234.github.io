 首先说下 / 下面包含: /bin /sbin /boot /dev /etc /home /lib /mnt /opt /proc /root /tmp /usr /var

 1. /bin： 可执行的二进制文件的目录。
 2. /sbin：放置系统管理员使用的可执行命令（反正我 暂时 没用过）
 3. /boot: 放置linux系统启用时用到的一些文件。
 4. /dev: 存放一些linux系统的设备文件，访问该目录下某个文件，相当于访问某个设备。常用挂载光驱mount
 5. /etc: 系统配置文件存放的目录。  
 &nbsp;&nbsp;&nbsp;&nbsp;/etc/hosts  配置域名  
 &nbsp;&nbsp;&nbsp;&nbsp;/etc/crontab 定时任务  
 &nbsp;&nbsp;&nbsp;&nbsp;php mysql nginx zsh vim 我都放在/etc下面了

 6. /home: 系统默认的用户家目录，新增用户也都在里面。
 7. /lib: 系统使用的函数库的目录。具体咋用 我也不知道,等以后发掘吧0.0
 8. /mnt: 光盘默认挂载点，通常光盘挂载于/mnt/cdrom下，也不一定，可以选择任意位置进行挂载。
 9. /opt: 额外所安装的应用程序目录,有些软件包我们可以将它安装在该目录中；(一般为空，某些应用软件安装需要这个目录 有的也会在/usr/local)
 10. /proc:  此目录的数据都在内存中，如系统核心，外部设备，网络状态.
 11. /root: 系统管理员root的家目录。
 12. /tmp: 没什么好说的，临时文件。
 13. /usr: 安装除操作系统本身外的一些应用程序或组件，一般可以认为linux系统上安装的应用程序默认都安装在此目录中； 我的项目什么的都放在这了。
 14. /var: 放置系统执行过程中经常变化的文件，如随时更改的日志文件 /var/log，/var/log/message

详细请参考：<http://www.cnblogs.com/dingn/p/5809298.html>