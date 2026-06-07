## mpv-config-bundle

> [dyphire/mpv-config](https://github.com/dyphire/mpv-config) 项目的GitHub Actions 自动构建，打包 mpv + ffmpeg + yt-dlp 一体便携版。
> 
> 配置使用[JiayuYangX/mpv-custom](https://github.com/JiayuYangX/mpv-custom)的个人配置文件，采用 [ModernZ](https://github.com/Samillion/ModernZ) 作为 OSC，脚本和设置参考自 [mpv-config](https://github.com/dyphire/mpv-config)，滤镜和着色器来源于 [mpv_PlayKit（原 mpv-lazy）](https://github.com/hooke007/mpv_PlayKit)。

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

### 预览

 ![1](https://github.com/JiayuYangX/mpv-custom/raw/main/pic1.jpg)

### 参考

* [hooke007 配置手册](https://hooke007.github.io/mpv-lazy/mpv.html)
* [mpv 官方文档（英文）](https://mpv.io/manual/master/)
* [mpv 文档汉化版-hooke007](https://github.com/hooke007/mpv_doc-CN)
* **上游项目**：[dyphire/mpv-config](https://github.com/dyphire/mpv-config)
* **上游项目**：[JiayuYangX/mpv-custom](https://github.com/JiayuYangX/mpv-custom)
