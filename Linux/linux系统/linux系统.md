# linux系统

## 基本信息

### Ubuntu

- 图形界面
- 已预先装好SSH

### 文件目录结构

- 只有根目录，没有盘符
- 目录和文件不能同名
- 文件或目录名字字符最多256个字符
- 针对多用户，所有每个用户都在/home下建立自己的目录
- /

  - 根目录

- /opt

	- 存放给主机额外安装软件目录，可供其他用户使用

- ~

	- 家目录

- 软硬链接示意

	- ![](Linux/linux%E7%B3%BB%E7%BB%9F/assets/345111733a75e2e6b9e6a130ab546086f104aa284efe23c518da4517ebe25075.png)

### 实用技巧

- 自动补全

	- 输入命令前几个字母后按tap

		- 存在歧义，按两下tap做选择

- ctrl+c 

	- 退出

- command [-options] [parameter]

	- [ ]表示可选

- 曾经使用过的命令

	- 上下按键
	- ctrl+c

		- 另起一行，退出选择，不执行目前选中命令

	- 子主题 3

- sudo ufw status

	- 查看防火墙状态

		- enable/disable 

### linux中绝大多数可执行文件保存在

- /bin

	- binary
	- 二进制可执行文件目录，主要用于具体应用

- /sbin

	- system binay
	- 系统管理员专用的二进制代码存放目录，主要用于系统管理

- /usr/bin

	- user commands for applications
	- 后期安装的一些软件

- /usr/sbin

	- super user commands for applications
	- 超级用户的一些管理程序

## 终端命令

### [文件和目录命令](%E6%96%87%E4%BB%B6%E5%92%8C%E7%9B%AE%E5%BD%95%E5%91%BD%E4%BB%A4.md)

### [拷贝和移动命令](%E6%8B%B7%E8%B4%9D%E5%92%8C%E7%A7%BB%E5%8A%A8%E5%91%BD%E4%BB%A4.md)

### [文件内容命令](%E6%96%87%E4%BB%B6%E5%86%85%E5%AE%B9%E5%91%BD%E4%BB%A4.md)

### [远程管理命令](%E8%BF%9C%E7%A8%8B%E7%AE%A1%E7%90%86%E5%91%BD%E4%BB%A4.md)

### [用户和权限](%E7%94%A8%E6%88%B7%E5%92%8C%E6%9D%83%E9%99%90.md)

### [系统信息](%E7%B3%BB%E7%BB%9F%E4%BF%A1%E6%81%AF.md)

### [其他命令](%E5%85%B6%E4%BB%96%E5%91%BD%E4%BB%A4.md)

### [[打包压缩]]

==sshcat.cn==

/usr/bin/passwd 用于修改用户密码的程序




