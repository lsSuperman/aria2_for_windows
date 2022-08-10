# **windows 平台使用 aria2 功能**
> aria2 for windows - The ultra fast download utility

## **1、如何使用Aria2**
##### 1. 拉取代码到本地（git clone 或 下载zip文件）

		git clone git@github.com:lsSuperman/aria2_for_windows.git
		
		or
		
		download zip file

##### 2. 打开aria2-1.36.0-win-64bit-build1文件夹，修改aria2.conf文件以下内容

		dir=C:\Users\Administrator\Desktop\（下载文件保存路径，改为你想要保存的绝对地址）
		
		log=D:\App\aria2_for_windows\aria2.log（日志文件，路径D:\app\改为项目存放路径）
		
		input-file=D:\app\aria2_for_windows\aria2.session（session文件，路径D:\app\改为项目存放路径）
		
		save-session=D:\app\aria2_for_windows\aria2.session（session文件，路径D:\app\改为项目存放路径）

##### 3.启动aria2服务
执行aria2-1.36.0-win-64bit-build1文件夹中HideRun.vbs。

##### 4.验证aria2是否启动
访问链接：http://localhost:6800/jsonrpc?jsoncallback=1 ，如果可以正常访问，说明Aria2服务启动成功了。

## **2、安装Chrome插件**
##### 1. 安装AriaNg

##### 2. 安装Tampermonkey
