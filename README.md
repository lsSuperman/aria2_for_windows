# **windows 平台使用 aria2 高速下载工具**

## **1、安装 Aria2**

##### 1. 拉取代码到本地（git clone 或 下载 zip 文件）

```
git clone https://github.com/lsSuperman/aria2_for_windows.git
```

##### 2. 打开 `aria2-1.36.0-win-64bit-build1` 文件夹，修改 `aria2.conf` 文件以下内容

```
dir=C:\Users\Administrator\Desktop\（下载文件保存地址，改为你想要保存的磁盘绝对地址）

log=D:\app\aria2_for_windows\aria2.log（日志文件，路径D:\app\改为本项目存放路径）

input-file=D:\app\aria2_for_windows\aria2.session（session文件，路径D:\app\改为本项目存放路径）

save-session=D:\app\aria2_for_windows\aria2.session（session文件，路径D:\app\改为本项目存放路径）
```

##### 3.启动 aria2 服务

- 执行 `aria2-1.36.0-win-64bit-build1` 文件夹中 `HideRun.vbs`。

##### 4.验证 aria2 是否启动

- 访问链接：http://localhost:6800/jsonrpc?jsoncallback=1 ，如果可以正常访问，说明 `Aria2` 服务启动成功了。

##### 5.停止 aria2 服务

- 执行 `aria2-1.36.0-win-64bit-build1` 文件夹中 `Stop.bat`。

## **2、如何使用**

> 以下两种方式任选其一即可。
>
> 使用方式适用于 Mac、Windows 等。
>
> chrome 插件安装方法：
>
> 1.在 `google` 浏览器中，点击右上角`自定义`按钮，找到`更多工具`->`扩展程序`，打开右上角`开发者模式`开关。
>
> 2.将 `crx` 文件夹中的扩展程序文件拖入 `google` 浏览器完成安装。
>
> > ps：安装失败时刷新页面重试.

### **1、Chrome 插件**

##### 1. 安装 AriaNg

##### 2. 安装 Tampermonkey

- 安装脚本：打开[百度网盘简易下载助手](https://greasyfork.org/zh-CN/scripts/418182-百度网盘简易下载助手-直链下载复活版)，点击安装即可。

##### 3、使用

- 1.登录百度网盘网页版，选择需要下载的文件，点击`简易下载助手`->`点击获取直连地址`->`发送至Aria2`。

- 2.打开 `AriaNg` 扩展即可管理下载任务及相关配置。

### **2、网盘直链下载助手**

##### 1. 安装 Tampermonkey

##### 2. [网盘直链下载助手](https://www.baiduyun.wiki/install.html#📖-使用教程)使用教程

- 打开链接，点击`安装网盘直链下载助手`按钮即可。

##### 3、使用

- 登录百度网盘网页版，选择需要下载的文件，点击`下载助手`即可选取多种方式使用。

## **3、🔗 相关链接**

> 工具链接
>
> > Aria2 GitHub：https://github.com/aria2/aria2
> >
> > AriaNg GitHub：https://github.com/mayswind/AriaNg
> >
> > Crx 搜搜：https://www.crxsoso.com
> >
> > Tampermonkey 脚本：https://greasyfork.org/zh-CN/scripts
>
> 参考文档
>
> > https://juejin.cn/post/6844903823803154446
> >
> > https://www.cnblogs.com/alphaprime/p/15781824.html
> >
> > https://github.com/jae-jae/Camtd

## **4、扩展（多线程下载器）**

> 参考文档
>
> > https://www.baiduyun.wiki/zh-cn/
