# 安装说明

只是安装了patchelf跟移动脚本到$PATH下，方便bash直接使用

copy libc到 /usr/lib/glibc/


# 使用说明

set_libc 文件名 libc版本
这样可以指定带符号版本的libc

set_libc 文件名 libc版本 libc文件名
这样可以指定加载特定libc，比如远程libc