<h1 align="center">
  <br>
  <a href="https://github.com/LuccaWang404/Ryujinx-ava-installers"><img src="./Ryujinx.ico" alt="Ryujinx-ava-installers" width="150"></a>
</h1>

<h5 align="center">
<b>🐲 龙神模拟器 (Ryjinx Emulator) [Avalonia UI 版] 安装程序</b>
</h5>

[ENGLISH](./README.md) | 简体中文

> [!NOTE]
> 鉴于Ryujinx项目已被`ryujinx-mirror`团队接手并重建, 我会在接下来的自动编译中引入来自[ryujinx-mirror/ryujinx](https://github.com/ryujinx-mirror/ryujinx)的新发布源。

<p>
       此仓库包含<b>自动编译的</b>龙神模拟器安装程序和安装程序以 <a href ="https://jrsoftware.org/isinfo.php">Inno Setup</a> 脚本编写的源代码。</br>
       此项目是一个<b>非官方的</b>、一个利用GH Actions自动编译Ryujinx模拟器安装程序的项目。</b></br>
       如果您想要了解各版本的更新内容，请前往官方仓库的wiki页面以查看最新的<a href="https://github.com/Ryujinx/Ryujinx/wiki/Changelog">Changelog（现已不可用）</a>。</br>
       此项目通过GitHub Actions定时检查更新、即时构建，与官方渠道的发行进度基本同步。</br>
</p>

> [!IMPORTANT]
> 1. **由于龙神模拟器已于2024年10月被迫删库跑路（真服了任天堂法务部），该项目不会继续更新（至少等到Ryujinx像citra一样被重建）。**</br>
> 2. **本人有幸fork了一个Ryujinx的镜像仓库，如有兴趣请前往[Ryujinx-Mirror](https://github.com/LuccaWang404/Ryujinx-Mirror)。**</br>
>	3. **如果该项目没有被DMCA takedown，所有已编译的安装程序均可到本项目的[Releases](https://github.com/LuccaWang404/Ryujinx-ava-installers/releases)页面下载。**

## 使用
运行安装程序，根据程序引导完成安装，龙神模拟器会安装在您的计算机上并完成文件关联。

***
> [!TIP]
  **什么是文件关联？**
> 文件关联是将一种类型的文件与一个可以打开它的程序建立起一种依存关系。</br>

举个栗子，`NSP程序包`（.nsp文件）在尚未关联时，必须在模拟器中手动加载才能运行；</br>
而执行关联后，`NSP程序包`在Windows中的默认打开程序则会被更改为`龙神模拟器`，</br>
此时双击文件就能直接开始运行`NSP包*` 内部的游戏程序。</br>
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

安装完毕后，请根据官方Wiki上的教程完成模拟器配置。

*~~估计现在也看不到了，自己去搜索吧~~*

[官方配置教程入口（现已不可用）](https://github.com/Ryujinx/Ryujinx/wiki/Ryujinx-Setup-&-Configuration-Guide)

> [!IMPORTANT]
> **运行本模拟器的计算机至少需配备8GB的运行内存，不达标的计算机强行运行可能会导致游戏卡成PPT或闪崩。**

## 最新版本
本项目已成功部署到Github Actions，每半小时同步一次版本更新，与官方渠道的发行进度基本同步。

> [!NOTE]
> **本项目纯属在空闲时间中用爱发电，而本人学业繁重，各种BUG的修复可能不及时，望大家多多包涵。**</br>
  **❗️此安装程序为Windows专供。官方提供的其他操作系统版本请前往官网下载（现在官网炸了，自求多福吧）。**

[下载入口（现已不可用）](https://ryujinx.org/download)

## 联系我
* 如果您有各种问题/建议，您可以联系 **[我的枉异邮箱](mailto:jh327063592@163.com)：jh327063592@163.com**。
* 如果您需要某特定版本的安装包（1.1.960+），与我联系后我也会尽快回复您。
* 如果您对本程序有任何建议或者需要帮助，亦或者发现了BUG，请提交issue。

## 开源许可
此项目根据[MIT协议](./LICENSE.txt)开放源代码。

了解更多请看[LICENSE](./LICENSE.txt)文件。
