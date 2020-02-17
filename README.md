<p align="center">
<img src="https://i.loli.net/2020/02/16/8wMe69NgqmBzUCZ.png">
</p>

<p align="center">
<img src="https://img.shields.io/github/stars/Andrew8102/suda-wifi-electron">
<a href="https://github.com/Andrew8102/suda-wifi-electron/releases"><img src="https://img.shields.io/github/v/release/Andrew8102/suda-wifi-electron.svg"></a>
<img src="https://img.shields.io/github/license/Andrew8102/suda-wifi-electron.svg">
</p>

# suda-wifi-electron

这是一个基于 Electron 开发的跨平台（Windows、macOS、Linux）的第三方苏大 Wifi 登录器 支持自动保存密码，支持手机端的 mac 绑定免认证登陆（仅支持 15 元包月用户），我们基于以下原因开发了它：

### 普通的上网认证方法：

打开电脑-连接苏大wifi-打开浏览器（或自动弹出）-输入密码（或一键填充）-点击登录（或回车）-认证成功（共6步）

### 有了软件的上网认证方法：

打开电脑-连上苏大wifi-打开本软件自动登录-认证成功（4步）

### 甚至你可以更加简化，wifi选择自动连上suda-wifi，并把这款软件设置为自启动项：

打开电脑-认证成功！（只需2步！）

打开即可一键连上suda-wifi，并且如果您是15元包月用户，可实现当天免认证使用suda-wifi，即模拟手机mac绑定功能

这个也是我第一个用来练手的 Electron 项目，所以代码会有些不大对劲，请多包涵

求个 star 谢谢大佬！！！！！

## 本软件适用于以下场合

带笔记本电脑上课、自习、图书馆，打开电脑即连网

本软件不适合于以下场合：

当你和别人共享宿舍路由器的中国移动wifi的时候、当你使用的是电信天翼网的时候

前者会把整个移动网挤掉，后者是根本连不上

## 本项目使用了以下开源项目

Node.js 

Electron

Bootstrap4

jQuery

## 使用说明

您可以[下载 Release 版](https://github.com/Andrew8102/suda-wifi-electron/releases) （包括安卓版）

如果打不开，可以试试[国内镜像Release](https://gitee.com/AndrewXu2018/suda-wifi-electron/releases)

或者您可以自行进行编译

先`clone`本项目

紧接着

```js
cd suda-wifi-electron
npm install   //安装依赖
npm run start     //开发调试
npm run make      //编译本项目
```

编译之后会输出到`out/make`文件夹内，编译模式会根据您的系统进行对应修改

或者（强烈推荐）
使用 `vue ui` 进行调试
在 `terminal` 或者 `cmd` 中 输入 `vue ui` 再导入本文件夹即可
前提是本机已经安装了 `vue-cli`

之后正常使用即可

### 首次打开

请首先连上`苏大 wifi`，并保证您可以打开校园网网站（保证已经分配给您 ip）

正常输入学号，密码，点击登陆即可正常使用

如果您是包月用户，每天只需要登陆一次即可，之后只要连上苏大 wifi，都可以使用免登陆上网功能

### 下次使用

如果您勾选了自动登录复选框，启动该程序就会自动登录

## 报错

1. 通讯异常，可能您已经断网：

您可能没连上苏大 wifi，或者系统未能给您分配正常的 ip

解决方法就是续租，刷新 ip

## 备注

解释一下为什么软件这么大，由于使用了Electron来进行开发，整个软件其实封装了一个完整的浏览器在里面，此外就是由于技术不成熟缘故，把一些不需要的开发时候的依赖全都塞进去了，这个会在未来重构的时候解决

安卓版非常小，喜欢的同学请自取，是同样的功能

## 联系我

[在 Issue 下联系我](https://github.com/Andrew8102/suda-wifi-electron/issues)，或者在 [lostwinds.cn 留言板模块](https://lostwinds.cn/%e7%95%99%e8%a8%80%e6%9d%bf.html/) 找到我们留言

By Andrew lostwinds.cn 2020
