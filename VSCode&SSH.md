# VSCode&amp;SSH

显然用平时使用的VSCode写代码比在全新Ubuntu虚拟机里用无插件vim修改代码来得舒适，同时见到了部分同学实际上是在本机写代码然后复制到虚拟机环境中编译执行的，效率很低。

## 优点/解决的问题：

1. 可以使用定制化的VScode环境来写实验代码，顺手👍🏻
2. 可以直接在实验环境中运行，不用手动复制了👋🏻
3. VScode的terminal/终端好用，多开时不用自己去拉窗口大小


## 指南

### 前情提要（面向VSCode初心者）

首先，VSCode是一个编辑器，不是一个编译器/IDE，不具备直接跑代码的能力，需要通过各种插件之类的配置来实现一个"看起来像IDE"的环境，要在VSCode里写得爽首先要在VSCode里写得爽。

具体的配置看以下这些可能有帮助

[VS Code 的 C/C++ 配置](https://blog.mgt.moe/posts/vscode-clang-ng/)

[官方文档](https://code.visualstudio.com/docs)

### VSCode remote (SSH)

如何用VSCode连接到远程服务器/虚拟机中

SSH有密码登录和密钥登陆两种，一般来说后者更加方便

[官方文档](https://code.visualstudio.com/docs/remote/ssh)

[ssh到VMware虚拟机中](https://zhuanlan.zhihu.com/p/146533515)


### 题外

新版的JetBrains系IDE（如PyCharm、GoLand、IntelliJ）也都集成了远程开发的功能（以前使用的是本地向远程同步文件的策略……）

[JetBrains系IDE的remote开发](https://www.jetbrains.com/help/idea/remote-development-a.html)
