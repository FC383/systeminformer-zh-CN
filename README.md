<p align="center">
    <a href="https://systeminformer.com">
        <img src="https://github.com/winsiderss/systeminformer/raw/master/SystemInformer/resources/systeminformer-128x128.png"/>
    </a>
    <h1 align="center">System Informer</h1>
    <h5 align="center">一款免费、强大、多功能工具，助你监控系统资源、调试软件并检测恶意软件。</h5>
    <h6 align="center">由 Winsider Seminars & Solutions, Inc. 出品</h6>
</p>
<p align="center">
    <a href="https://github.com/winsiderss/systeminformer/actions/workflows/msbuild.yml"><img src="https://img.shields.io/github/actions/workflow/status/winsiderss/systeminformer/msbuild.yml?branch=master&style=for-the-badge"/></a>
    <a href="https://github.com/winsiderss/systeminformer/graphs/contributors"><img src="https://img.shields.io/github/contributors/winsiderss/systeminformer.svg?style=for-the-badge&color=blue"/></a>
    <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge&color=blue"/></a>
</p>
<p align="center">
    <a href="https://systeminformer.com/downloads"><img src="https://img.shields.io/github/downloads/winsiderss/si-builds/total.svg?style=for-the-badge&color=blue"/></a>
    <a href="https://somsubhra.github.io/github-release-stats/?username=winsiderss&repository=systeminformer"><img src="https://img.shields.io/github/downloads/winsiderss/systeminformer/total.svg?style=for-the-badge&color=blue&label="/></a>
    <a href="https://sourceforge.net/projects/processhacker/files/stats/timeline?period=monthly"><img src="https://img.shields.io/sourceforge/dt/processhacker.svg?style=for-the-badge&color=blue&label="/></a>
</p>
<p align="center">
    <a href="https://discord.com/invite/k2MQd2DzC2"><img src="https://img.shields.io/badge/Discord-grey?style=for-the-badge&logoColor=white&logo=discord"/></a>
    <a href="https://x.com/systeminformer"><img src="https://img.shields.io/badge/Twitter-grey?style=for-the-badge&logoColor=white&logo=x"/></a>
    <a href="https://systeminformer.com"><img src="https://img.shields.io/badge/Website-grey?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTIgMTIiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PGNpcmNsZSBjeD0iNiIgY3k9IjYiIHI9IjUuNSIgc3Ryb2tlPSJ3aGl0ZSIvPjxlbGxpcHNlIGN4PSI2IiBjeT0iNiIgcng9IjUuNSIgcnk9IjIiIHRyYW5zZm9ybT0icm90YXRlKDkwIDYgNikiIHN0cm9rZT0id2hpdGUiLz48cGF0aCBkPSJNMSA2SDExIiBzdHJva2U9IndoaXRlIiBzdHJva2UtbGluZWNhcD0icm91bmQiLz48L3N2Zz4="/></a>
</p>

---

> ## 🇨🇳 简体中文汉化版（非官方）
>
> 本项目是基于 [System Informer](https://github.com/winsiderss/systeminformer) 的 **非官方简体中文（zh-CN）汉化版**。
>
> - **性质**：仅将用户界面文本翻译为简体中文，未改动任何功能逻辑。
> - **许可**：遵循上游 [MIT 许可](./LICENSE.txt)，版权归原作者 [Winsider Seminars & Solutions, Inc.](https://systeminformer.com) 所有；第三方组件声明见 [`COPYRIGHT.txt`](./COPYRIGHT.txt)。
> - **来源**：上游仓库 <https://github.com/winsiderss/systeminformer>（汉化基于提交 `b5c72ff40`）。
> - **声明**：本汉化版与上游官方**无隶属关系**，不代表官方发布；如遇问题请勿向上游报告。
> - 如需英文原版或官方支持，请访问 [上游仓库](https://github.com/winsiderss/systeminformer) 与 [官方网站](https://systeminformer.com)。

## 系统要求

Windows 10 或更高版本，32 位或 64 位。

## 功能特性

* 详细且带高亮的系统活动概览。
* 图表与统计信息，助你快速定位资源占用大户与失控进程。
* 无法编辑或删除某个文件？查明哪些进程正在占用它。
* 查看哪些程序有活动的网络连接，并在必要时将其关闭。
* 获取磁盘访问的实时信息。
* 查看支持内核模式、WOW64 与 .NET 的详细堆栈跟踪。
* 超越 services.msc：创建、编辑并控制服务。
* 小巧、便携，无需安装。
* 100% [自由软件](https://www.gnu.org/philosophy/free-sw.en.html)
  （[MIT](https://opensource.org/licenses/MIT)）

## 构建项目

需要 Visual Studio（2022 或更高版本）。

克隆仓库后，运行 `build` 目录下的 `build_init.cmd`；除非工具或第三方
库有更新，否则无需再次运行。

运行 `build` 目录下的 `build_release.cmd` 即可编译项目，或直接加载
`SystemInformer.sln` 与 `Plugins.sln` 解决方案（如果你更习惯使用
Visual Studio 构建项目）。

你可以下载免费的
[Visual Studio Community 版](https://www.visualstudio.com/vs/community/)
来构建 System Informer 源代码。

更多信息或构建遇到问题时，请参阅 [构建说明](./build/README.md)。

## 改进 / 缺陷反馈

请使用
[GitHub 问题跟踪器](https://github.com/winsiderss/systeminformer/issues)
报告问题或建议新功能。

## 设置

如果你从 USB 驱动器运行 System Informer，可能也想把其设置一并保存
到该驱动器上。为此，请在 SystemInformer.exe 所在目录下创建一个名为
"SystemInformer.exe.settings.xml" 的空文件。你可以通过 Windows 资源
管理器完成：

1. 确保在 工具 > 文件夹选项 > 查看 中取消勾选"隐藏已知文件类型的扩
   展名"。
2. 在文件夹中右键，选择 新建 > 文本文件。
3. 将文件重命名为 SystemInformer.exe.settings.xml（删除 ".txt" 扩展
   名）。
