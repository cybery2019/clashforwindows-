
clashforwindows图文教程（全流程，详解）
## 1、简介
Clash 是一个使用 Go 语言编写，基于规则的跨平台代理软件核心程序。

Clash for Windows 是目前在 Windows 上唯一可用的图形化 Clash 分支。通过 Clash API 来配置和控制 Clash 核心程序，便于用户可视化操作和使用。

支持的协议： `Vmess`, `Shadowsocks,`` Snell `, `SOCKS5` , `ShadowsocksR`。
## 2、下载地址
**Clash for Windows中文版客户端：**[点击前往下载](https://www.hereitis.cn/soft/clashforwindowszh "点击前往下载")

## 3、配置使用教程
1、通过上面链接下载解压后，打开其中的Clash for Windows.exe（部分电脑上没有显示后缀，即文件名叫 Clash for Windows）
![](https://www.hereitis.cn/profile/upload/2022/07/06/81040298-dbcd-4cb1-9ebc-5c13115d959a.jpg)

2、通过订阅链接下载配置文件，在(Profiles)配置文件一栏里面，复制你购买订阅的链接URL，然后点击download（下载）按钮下载订阅文件,
![](https://www.hereitis.cn/profile/upload/2022/07/06/a4dd324a-c862-4f67-b284-a984ee591064.png)

3、切换到proxies（代理）一栏，会看到很多节点，单击无线图标可以查看延迟等。选择你的节点，用鼠标点下即可。其他不懂的不要动。
![](https://www.hereitis.cn/profile/upload/2022/07/06/30e9340f-d1f6-4077-9e8b-e88a98170b30.png)

4、点击常规,打开系统代理和开机启动两项即可。如果需要局域网共享可以打开允许局域网连接，默认是关闭。
![](https://www.hereitis.cn/profile/upload/2022/07/06/e826aa03-ac82-4b23-8cc8-7db1e79e11fb.png)

这样，打开浏览器即可访问代理所属环境的网站了。

## 4、代理模式（小白可以不看）
全局（Global）：所有请求直接发往代理服务器
规则（Rule）：所有请求根据配置文件规则进行分流
直连（Direct）：所有请求直接发往目的地

## 5、上不了网（无法访问，请检查代理）
方法一：删除先前的配置文件，然后通过url重新下载就可以解决问题了。
方法二：在任务栏的搜索框中输入“cmd”，右键点击命令提示符，选择以管理员身份运行，在管理员：命令提示符窗口中执行以下的命令：netsh winsock reset 回车。然后重启电脑，再开clash，Ok
方法三：打开系统设置---网络和Internet设置---关闭代理，退出clash,在重启clash即可（如下图）。
![](https://www.hereitis.cn/profile/upload/2022/07/06/08173ac1-1ff3-438c-919f-17c16c584399.jpg)
