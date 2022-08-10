# **windows 平台使用 aria2 高速下载工具**

> aria2 for windows - The ultra fast download utility

## **1、安装 Aria2**

##### 1. 拉取代码到本地（git clone 或 下载 zip 文件）

    git clone https://github.com/lsSuperman/aria2_for_windows.git

or

手动 download zip file

##### 2. 打开 aria2-1.36.0-win-64bit-build1 文件夹，修改 aria2.conf 文件以下内容

    dir=C:\Users\Administrator\Desktop\（下载文件保存路径，改为你想要保存的绝对地址）

    log=D:\App\aria2_for_windows\aria2.log（日志文件，路径D:\app\改为项目存放路径）

    input-file=D:\app\aria2_for_windows\aria2.session（session文件，路径D:\app\改为项目存放路径）

    save-session=D:\app\aria2_for_windows\aria2.session（session文件，路径D:\app\改为项目存放路径）

##### 3.启动 aria2 服务

执行 aria2-1.36.0-win-64bit-build1 文件夹中 HideRun.vbs。

##### 4.验证 aria2 是否启动

访问链接：http://localhost:6800/jsonrpc?jsoncallback=1 ，如果可以正常访问，说明 Aria2 服务启动成功了。

##### 5.停止 aria2 服务

执行 aria2-1.36.0-win-64bit-build1 文件夹中 Stop.bat。

## **2、安装 Chrome 插件**

**安装流程**  
1.在 google 浏览器中，点击右上角`自定义`按钮，找到`更多工具`->`扩展程序`，打开右上角`开发者模式`开关。  
2.将 crx 文件中的扩展程序文件拖入 google 浏览器，进行安装。

##### 1. 安装 AriaNg

##### 2. 安装 Tampermonkey

添加脚本：https://greasyfork.org/zh-CN/scripts/418182-百度网盘简易下载助手-直链下载复活版

ps：可使用其他脚本替换

## **3、使用**

##### 1.登录百度网盘网页版，选择需要下载的文件，点击`简易下载助手`->`点击获取直连地址`->`发送至Aria2`。

##### 2.打开 AriaNg 扩展即可管理下载任务，及相关配置管理。

## **4、🔗 相关链接**

> 工具链接
>
> > Aria2 GitHub：https://github.com/aria2/aria2  
> > AriaNg GitHub：https://github.com/mayswind/AriaNg  
> > Crx 搜搜：https://www.crxsoso.com  
> > Tampermonkey 脚本：https://greasyfork.org/zh-CN/scripts
>
> 参考文档
>
> > https://juejin.cn/post/6844903823803154446  
> > https://www.cnblogs.com/alphaprime/p/15781824.html  
> > https://github.com/jae-jae/Camtd
