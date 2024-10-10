<h1 align="center">
  <br>
  <a href="https://github.com/LuccaWang404/Ryujinx-ava-installers"><img src="./Ryujinx.ico" alt="Ryujinx-ava-installers" width="150"></a>
</h1>

<h5 align="center">
<b>Ryujinx [Avalonia UI] Installer</b>
</h5>

ENGLISH | [简体中文](./README_CN.md)

> [!NOTE]
> Since the Ryujinx project has been reconstructed by `ryujinx-mirror`, a new release source (from [ryujinx-mirror/ryujinx](https://github.com/ryujinx-mirror/ryujinx)) will be added to this repository.

<p>
       This repository contains the auto-compiled releases of Ryujinx emulator installer and the source code written in <a href ="https://jrsoftware.org/isinfo.php">Inno 
       Setup</a> Script.</br>
       If you want to check out the update details of each version, please visit the official wiki page to see the <a href="https://github.com/Ryujinx/Ryujinx/wiki/Changelog">Official Changelog (Not available now)</a>.</br>
       This project can check for updates regularly and built the installers instantly by GitHub Actions, so it is generally synchronized with the progress of the ryujinx release channel.</br>
</p>

> [!IMPORTANT]
> 1. **As Ryujinx's repository was forced to be deleted by Nintendo's legal department in October 2024, this project will no longer be updated (At least until the Ryujinx project is reconstructed like citra).**</br>
> 2. **Thankfully, I forked a mirror repository of Ryujinx before it's unavailable. If you are interested in the source code of the Ryujinx project, [Ryujinx-Mirror](https://github.com/LuccaWang404/Ryujinx-Mirror) may help you.**</br>
>	3. **If this project is not taken down due to DMCA, all compiled installers can be downloaded from the [Releases](https://github.com/LuccaWang404/Ryujinx-ava-installers/releases) page.**

## Usage
Run the installer, follow the prompts and complete the installation process, Ryujinx [Avalonia UI] will be installed on your PC and finish file association.

***
> [!TIP]
  **What is file association?**</br>
> File association is to establish a dependency between a type of file and a program that can open it.</br>

For example, The `NSP package` (.nsp file) must be manually loaded in the emulator before it can be run when it is not associated.</br>
After the association, the default associated program of the `NSP package` in Windows is `Ryujinx`.</br>
Now, double-click the file, you can start the game contains in the `NSP package*` directly.</br>
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

After installation, please follow the official guide to finish configuration of the emulator. 

[Setup & Configuration Guide (Not available now)](https://github.com/Ryujinx/Ryujinx/wiki/Ryujinx-Setup-&-Configuration-Guide)

> [!IMPORTANT]
>**To run this emulator, your PC must be equipped with at least 8GiB of RAM; failing to meet this requirement may result in a poor gameplay experience or unexpected crashes.**

## Latest Build
As the project was successfully deployed to GitHub Actions, all versions will be compiled automatically and generally synchronized with the progress of the Ryujinx release channel.

GitHub Actions will check updates per 30 minutes, keep this buid synchronized with the official version.

> [!NOTE]
**I am working on this project in my free time. As a student, I may not be able to fix the bugs in time. I really appreciate your understanding.**</br>
**These builds are only for Windows. Official builds for Linux / macOS can be found on the [Official Website (Not available now)](https://ryujinx.org/download).**

## Contact
* If you have any promblems/suggestions, please contact me via [jh327063592@163.com](mailto:jh327063592@163.com).
* If you need a specific version of the installer(1.1.960+), mail me and I will reply you ASAP.
* If you have any suggestions or need help with this program, or if you find a BUG, please submit an issue.

## License
This software is licensed under the terms of the [MIT License](./LICENSE.txt).

See [LICENSE](./LICENSE.txt) for more details.
