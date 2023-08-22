<h1 align="center">
  <br>
  <a href="https://github.com/LuccaWang404/Ryujinx-ava-installers"><img src="https://pic.imgdb.cn/item/64e25563661c6c8e54b74b17.png" alt="Ryujinx-ava-installers" width="150"></a>
</h1>

<h5 align="center">
<b>🐲 龙神模拟器 (Ryujinx Emulator) [Avalonia UI 版] 安装程序</b>
</h5>

[ENGLISH](./README_EN.md) | 简体中文

<p align="center">
       此仓库包含龙神模拟器 <b>[Avalonia UI 版]</b> 安装程序的发行版本和安装程序以 <a href ="https://jrsoftware.org/isinfo.php">Inno Setup</a> 脚本编写的源代码。</br>
       此项目为一个<b>非官方的</b>龙神任天堂Switch模拟器安装程序构建版本。</b></br>
       如果您想要了解各版本的更新内容，请前往官方仓库的发布页面以查看<a href="https://github.com/Ryujinx/Ryujinx/wiki/Changelog">Official Changelog</a>。</br>
       <b>❗️注意：本项目与龙神模拟器官方项目没有任何直接联系。如需要了解更多细节，请前往<a href="https://github.com/Ryujinx/Ryujinx">官方仓库。</a>❗️</b></br>
       <b>❗️另外，由于本安装程序仍处于测试阶段，所有功能可能均不稳定并可能导致数据丢失，请谨慎使用❗️</b></br>
       此项目通过GitHub Actions定时检查更新、即时构建，与官方渠道的发行进度基本同步。</br>
       该项目源代码可在GitHub上以<a href="./LICENSE.txt">MIT许可证</a>获取。</br>
</p>

## 使用
运行安装程序，根据程序引导完成安装，龙神模拟器 [Avalonia UI 版] 会安装在您的计算机上并完成文件关联。

***
> **TIP：什么是文件关联？**

文件关联是将一种类型的文件与一个可以打开它的程序建立起一种依存关系。

举个例子来说，NSP程序包（.nsp文件）在尚未关联时，必须在模拟器中手动加载才能运行。

而关联后，NSP程序包在Windows中的默认关联程序是龙神模拟器，

此时双击文件就能直接开始运行NSP包* 内部的游戏程序。

❗️ ***NSP包仅限游戏本体，非更新、DLC包***

***

**安装完毕后会被关联的文件类型：**

| 文件类型 | 关联后显示名称                      |
| -------- | ----------------------------------- |
| .nsp     | Nintendo Switch Application Package |
| .xci     | Nintendo Switch Gamecard Image      |
| .nca     | Nintendo Switch Executable File     |
| .nro     | Nintendo Switch Executable File     |
| .nso     | Nintendo Switch Executable File     |
| .kip     | Nintendo Switch Executable File     |

安装完毕后，请根据官方教程完成模拟器配置。

~~如果有不认识的词句，请自行翻译。~~

[官方配置教程入口](https://github.com/Ryujinx/Ryujinx/wiki/Ryujinx-Setup-&-Configuration-Guide)

**❗️重要的事情说三遍❗️** 

**运行本模拟器的计算机至少需配备8GB的运行内存，不达标的计算机强行运行可能会导致游戏卡成PPT或闪崩。**

## 最新版本
本项目已成功部署到Github Actions，每十五分钟同步一次版本更新，与官方渠道的发行进度基本同步。

本项目纯属在空闲时间中用爱发电，而本人学业繁重，各种BUG的修复可能不及时，望大家多多包涵。

**此安装程序为Windows专供。官方提供的其他操作系统版本请前往官网下载。**

[下载入口](https://ryujinx.org/download)

## 联系我
如果您有各种问题/建议，欢迎联系 **[我的枉异邮箱](mailto:jh327063592@163.com)：jh327063592@163.com**。

如果您需要某特定版本的安装包（1.1.960+），与我联系后我也会尽快回复您。

如果您对本程序有任何建议或者需要帮助，亦或者发现了BUG，请提交issue。

## 开源许可
此项目根据[MIT协议](./LICENSE.txt)开放源代码。

了解更多请看[LICENSE](./LICENSE.txt)文件。

***

## ~~吐槽~~

~~GitHub Actions真是离谱，定时运行但又好像没有完全定时~~

~~给它订了每半小时运行一次，结果有时候心心念念盼了几个小时B动静没有~~

~~倒好，一个配置文件的debug就搞了一整天，真™*了狗了~~