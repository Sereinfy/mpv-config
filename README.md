## mpv-config-bundle

> 基于 [dyphire/mpv-config](https://github.com/dyphire/mpv-config) 的个性化配置，增加 GitHub Actions 自动构建，打包 mpv + ffmpeg + yt-dlp 一体便携版。

### 项目介绍

本项目为 windows 下 [mpv](https://github.com/mpv-player/mpv) 播放器的配置文件，应放入`mpv.exe`所在目录的`portable_config`文件夹内，解压即用。

PS：自行编辑配置文件时，注意编码格式应为 UTF-8，换行符为 Unix，否则 MPV 可能无法识别

### GitHub 自动构建

本仓库通过 GitHub Actions 自动构建便携式 mpv 播放器整合包，包含：

- **mpv** — [dyphire/mpv-winbuild](https://github.com/dyphire/mpv-winbuild) 个性化编译版
- **FFmpeg** — 同源的 ffmpeg.exe
- **yt-dlp** — 最新版 yt-dlp.exe

### mpv 客户端

- [mpv 官网](https://mpv.io/installation) — 第三方编译版列表
  - [dyphire/mpv-winbuild](https://github.com/dyphire/mpv-winbuild/releases) — 含个人补丁的编译版
  - [shinchiro/mpv-winbuild-cmake](https://github.com/shinchiro/mpv-winbuild-cmake/releases) — 标准编译版
  - [zhongfly/mpv-winbuild](https://github.com/zhongfly/mpv-winbuild/releases) — 每日构建版
- [mpv.net](https://github.com/mpvnet-player/mpv.net) — 成熟的 mpv 前端

### 脚本着色器说明

脚本功能介绍详见上游项目的 [脚本说明-wiki](https://github.com/dyphire/mpv-config/wiki/脚本说明)，着色器相关参数见 `mpv.conf` 中的配置组。

### 预览

 ![image-20231103224421000](https://cdn.jsdelivr.net/gh/dyphire/PicGo/img/2023/11/03/image-20231103224421000.png)

![image-20231103224540075](https://cdn.jsdelivr.net/gh/dyphire/PicGo/img/2023/11/03/image-20231103224540075.png)

![image-20231103224557019](https://cdn.jsdelivr.net/gh/dyphire/PicGo/img/2023/11/03/image-20231103224557019.png)

### 参考

* [hooke007 配置手册](https://hooke007.github.io/mpv-lazy/mpv.html)
* [mpv 官方文档（英文）](https://mpv.io/manual/master/)
* [mpv 文档汉化版-hooke007](https://github.com/hooke007/mpv_doc-CN)
* **上游项目**：[dyphire/mpv-config](https://github.com/dyphire/mpv-config) — 本配置的来源与基础，感谢原作者
