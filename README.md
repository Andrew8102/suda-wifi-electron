# suda-wifi-electron

![截屏2020-02-16下午12.41.01.png](https://i.loli.net/2020/02/16/8wMe69NgqmBzUCZ.png)

这是一个基于 Electron 开发的跨平台的第三方苏大 Wifi 登录器
支持自动保存密码，支持手机端的 mac 绑定免认证登陆（仅支持 15 元包月用户）
这个也是我第一个用来练手的 Electron 项目，所以代码会有些不大对劲，请多包涵

求个 star 谢谢大佬！！！！！

## 本项目使用了

Node.js
Electron
Bootstrap4
jQuery

## 使用说明

您可以自行进行编译

先`clone`本项目

紧接着

```js
cd 本目录
npm install   //安装依赖
npm start     //开发调试
npm make      //编译本项目
```

编译之后会输出到`out/make`文件夹内，编译模式会根据您的系统进行对应修改

或者（强烈推荐）
使用 vue ui 进行调试
在 terminal 或者 cmd 中 输入 vue ui 再导入本文件夹即可
前提是本机已经安装了 vue-cli

之后正常使用即可

### 首次打开

请首先连上苏大 wifi，并保证您可以打开校园网网站（保证已经分配给您 ip）

正常输入学号，密码，点击登陆即可正常使用

如果您是包月用户，每天只需要登陆一次即可，之后只要连上苏大 wifi，都可以使用免登陆上网功能

### 下次使用

如果您勾选了自动登录复选框，启动该程序就会自动登录

## 报错

1. 通讯异常，可能您已经断网：

您可能没连上苏大 wifi，或者系统未能给您分配正常的 ip

解决方法就是续租，刷新 ip

## 联系我

issue 本项目，或者在 [lostwinds.cn 留言板模块](https://lostwinds.cn/%e7%95%99%e8%a8%80%e6%9d%bf.html/) 找到我们留言

By Andrew lostwinds.cn 2020
