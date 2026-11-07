# AMV Studio

AMV Studio 的 Windows 安装包与应用更新发布仓库。

[下载最新版本](https://github.com/XiangZi7/AMV-Studio-Releases/releases/latest)

- **setup.exe**：Windows x64 安装版。安装后可在「设置 → 关于与更新」检查更新。
- **portable.zip**：解压后运行 AMV Studio.exe，需要 WebView2 Runtime。
- **SHA256SUMS.txt**：下载文件的 SHA-256 校验和。
- **latest.json / .sig**：应用内更新清单与更新签名，供更新器自动使用。

首次发布完成前，下载入口暂时没有安装包。源码在独立的私有仓库维护，此仓库仅用于分发正式发布文件。

现有不带更新器的 0.1.0 版本需要手动安装新版一次，之后即可在应用内更新。工程、素材和设置保存在本机应用数据目录。
