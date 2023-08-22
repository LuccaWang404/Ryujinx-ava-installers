<h1 align="center">
  <br>
  <a href="https://github.com/LuccaWang404/Ryujinx-ava-installers"><img src="https://pic.imgdb.cn/item/64e25563661c6c8e54b74b17.png" alt="Ryujinx-ava-installers" width="150"></a>
</h1>

<h5 align="center">
<b>Ryujinx [Avalonia UI] Installer</b>
</h5>

ENGLISH | [简体中文](./README.md)

<p align="center">
       This repository contains the releases of Ryujinx [Avalonia UI] installer and the installer source code written in <a href ="https://jrsoftware.org/isinfo.php">Inno 
       Setup</a> Script.</br>
       This projrect is a <b>non-official</b> installer build of the Nintendo Switch emulator <a href="https://github.com/Ryujinx/Ryujinx">Ryujinx</a>.</br>
       If you want to check out the update details of each version, please go to the official release page to see the <a href="https://github.com/Ryujinx/Ryujinx/wiki/Changelog">Official Changelog</a>.</br>
       <b>❗️IMPORTANT：This project is not affiliated with Ryujinx in ANYWAY. For more details，please see the<a href="https://github.com/Ryujinx/Ryujinx">Offifial Repository of Ryujinx</a>❗️</b></br>
       <b>❗️Also, as this installer is still in the testing stage, all functions may be unstable and may cause data loss, please use it with caution❗️</b></br>
       <b>❗️I WILL NOT be responsible for any data loss caused by this program❗️</b></br>
       This project is checked for updates regularly and built instantly through GitHub Actions, so it is generally synchronized with the progress of the Ryujinx release channel.</br>
       The source code is available on Github under the <a href="./LICENSE.txt">MIT license</a>. </br>
</p>

## Usage
Run the installer, follow the prompts and complete the installation process, Ryujinx [Avalonia UI] will be installed on your PC and finish file association.

***
> **TIP：What is file association?**

File association is to establish a dependency between a type of file and a program that can open it.

For example, The NSP package (.nsp file) must be manually loaded in the emulator before it can be run when it is not associated.

After the association, the default associated program of the NSP package in Windows is the Ryujinx.

Now, double-click the file, you can start the game in the NSP package* directly.

❗️ ***The NSP file can only be the base NSP, not Update/DLC packages.***

***

**File types which will be associated:**

| File type | Display name after association     |
| -------- | ----------------------------------- |
| .nsp     | Nintendo Switch Application Package |
| .xci     | Nintendo Switch Gamecard Image      |
| .nca     | Nintendo Switch Executable File     |
| .nro     | Nintendo Switch Executable File     |
| .nso     | Nintendo Switch Executable File     |
| .kip     | Nintendo Switch Executable File     |

After the installation, please follow the official guide to finish configuration of the emulator. 

[Setup & Configuration Guide](https://github.com/Ryujinx/Ryujinx/wiki/Ryujinx-Setup-&-Configuration-Guide)

**❗️IMPORTANT❗️**

**To run this emulator, your PC must be equipped with at least 8GiB of RAM; failing to meet this requirement may result in a poor gameplay experience or unexpected crashes.**

## Latest Build
As the project was successfully deployed to GitHub Actions, all versions will be compiled automatically and generally synchronized with the progress of the Ryujinx release channel.

GitHub Actions will check updates per 30 minutes, keep this buid synchronized with the official version.

**I am working on this project in my free time. As a student, I may not be able to fix the bugs in time.**

**❗️These builds are only for Windows. Official builds for Linux / macOS can be found on the [Official Website](https://ryujinx.org/download).**

## Contact
If you have any promblems/suggestions, please contact me via [jh327063592@163.com](mailto:jh327063592@163.com).

If you need a specific version of the installer(1.1.960+), mail me and I will reply you ASAP.

If you have any suggestions or need help with this program, or if you find a BUG, please submit an issue.


## License
This software is licensed under the terms of the [MIT License](./LICENSE.txt).

See [LICENSE](./LICENSE.txt) for more details.
