<p align="center"><img src="assets/icon.png" width="100" alt="咪咪 图标"></p>

# 咪咪

**把文件浏览、整理和双列移动放进一个窗口。**

![产品介绍](assets/banner.svg)

[![下载](https://img.shields.io/badge/下载-DMG-brightgreen)](https://github.com/jhtnba/mimi/releases/latest) [![版本](https://img.shields.io/badge/版本-0.2.51-blue)](https://github.com/jhtnba/mimi/releases) [![系统](https://img.shields.io/badge/平台-macOS-black)](docs/INSTALL.md)

[下载应用](https://github.com/jhtnba/mimi/releases/latest) · [使用方法](docs/GUIDE.md) · [更新记录](CHANGELOG.md) · [常见问题](docs/FAQ.md) · [反馈问题](https://github.com/jhtnba/mimi/issues/new/choose)

## 为谁准备

从 Windows 换到 Mac，还不习惯 Finder 的文件管理方式？试试咪咪资源管理器。

熟悉的**左侧目录树**，让文件夹层级清晰可见。目录树随当前路径自动展开，深入多层文件夹，也能看清自己所在的位置。搭配顶部路径导航和右侧文件列表，浏览、定位文件更加直观。

支持**拖动移动文件、剪切与粘贴**，让你在 macOS 上，也能沿用熟悉、顺手的 Windows 操作习惯。

使用 **Swift 原生开发**，专注日常文件管理，界面简洁，减少不必要的功能干扰。

**换了系统，也能保留熟悉的手感。**

<!-- mimi-extra-screenshots -->
### 双列浏览，整理文件更直观

左右两列独立浏览目录，各自支持目录树和路径导航。列表与网格可以搭配使用，文件也能在两列之间拖动移动。

![咪咪双列浏览：左侧列表与右侧网格，各有独立目录树](assets/dual-pane.png)

### 网格视图，直观浏览文件

以图标方式查看文件和文件夹，按需调整图标大小，并保留左侧目录树，方便浏览多层目录。

![咪咪网格视图与左侧目录树](assets/grid-view.png)
<!-- /mimi-extra-screenshots -->

## 主要功能

| 功能 | 具体用途 |
|---|---|
| 双列浏览 | 左右两列独立导航，适合对照文件夹、整理和移动文件。 |
| 列表与网格 | 列表查看文件信息，网格查看图片、视频等受支持文件的缩略图。 |
| 目录树与收藏 | 逐层展开目录，拖入文件夹建立收藏，拖动调整收藏顺序。 |
| 日常文件操作 | 打开、复制、剪切、粘贴、重命名、压缩及移到废纸篓。 |
| 可定制工具栏 | 调整按钮显示与顺序，搜索栏也能换位。 |
| 跨目录移动 | 支持拖放移动；同名项目不直接覆盖。 |

## 下载与安装

当前版本 **0.2.51（build 57）**。当前发布包面向 **Apple Silicon Mac**，要求 **macOS 15 或更新版本**。

1. 前往 [Releases](https://github.com/jhtnba/mimi/releases/latest)，下载 `咪咪-0.2.51.dmg`。
2. 打开 DMG，把 App 拖到“应用程序”。
3. 从“应用程序”启动。详细步骤见[安装指南](docs/INSTALL.md)。

## 第一次使用

1. 打开应用，双击目录进入；双击文件使用系统默认应用打开。
2. 点击侧栏箭头展开目录；使用路径栏和前进、后退按钮导航。
3. 在列表表头选择排序；搜索框筛选当前目录，不能代替全盘搜索。

[查看完整操作指南 →](docs/GUIDE.md)

## 使用前须知

- 当前不提供网络连接功能。
- 缩略图依赖 macOS Quick Look；部分视频可能无法生成预览。
- FFmpeg 取帧为可选后备，本应用未打包 FFmpeg。
- 部分 Finder 操作可能需要自动化授权；文件操作仍受磁盘权限约束。
- 属于个人维护版本，尚未完成全面鼠标键盘验收，不承诺覆盖所有文件系统。

## 问题反馈

通过 [Issues](https://github.com/jhtnba/mimi/issues/new/choose) 描述复现步骤、macOS 版本、应用版本和预期结果。截图请遮挡个人路径、用户名和文件内容；不要提交密码、令牌或原始私人文件。

## 更多应用

[咪咪](https://github.com/jhtnba/mimi) · [IINB](https://github.com/jhtnba/iinb) · [拾回](https://github.com/jhtnba/shihui) · [应用总览](https://github.com/jhtnba/mac-apps)

本页面只列出已有资料能核实的功能，不把计划功能写成已实现；未做过的兼容性和交互测试不作保证。
