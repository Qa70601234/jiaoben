# jiaoben
各类脚本
> install.sh
```
全自动安装默认
用户：root
密码: MoeClub.org

# Debian/Ubuntu:
apt-get update
apt-get install -y xz-utils openssl gawk file
# RedHat/CentOS:
yum update
yum install -y xz openssl gawk file
wget https://moeclub.org/attachment/LinuxShell/InstallNET.sh
chmod a+x InstallNET.sh
bash InstallNET.sh -d 10 -v 64 -a
系统选择详解：

# 全自动安装Ubuntu 16.04 x64：
bash InstallNET.sh -u 16.04 -v 64 -a
# 全自动安装Debian 9 x64：
bash InstallNET.sh -d 9 -v 64 -a
# 全自动安装Debian 10 x64(中科大镜像源，用于国内服务器)：
bash InstallNET.sh -d 10 -v 64 -a --mirror 'http://mirrors.ustc.edu.cn/debian/'
# 全自动安装CentOS 6.7 x64：
bash InstallNET.sh -c 6.7 -v 64 -a
腾讯云轻量 DD win

apt-get update
apt-get install -y xz-utils openssl gawk file wget screen && screen -S os
wget --no-check-certificate -qO InstallNET.sh 'https://tutu.bid/bash/InstallNET.sh' && bash InstallNET.sh -dd 'https://tutu.bid/os/dd/win10ltsc_x64.tar.gz'
一键添加 / 删除 swap 虚拟内存展开目录
脚本不支持 OpenVZ 架构，安装会自动退出。
输入命令后根据选项进行操作，记得添加 swap 的时候填写纯数字，默认单位为 M。

wget https://www.moerats.com/usr/shell/swap.sh && bash swap.sh
```
