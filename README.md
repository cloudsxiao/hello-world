# hello-world
just a repository
首先,su,su -这两个命令都能获得root权限,

但root的密码是不能随便交给别人的,这时就需要sudo命令了,

使用用户自己的密码,临时赋予一般用户root权限,

sudo的运行过程是这样的:

检查用户是否在/etc/sudoers的列表中,
如果在,以root权限执行命令,
取消用户的root
