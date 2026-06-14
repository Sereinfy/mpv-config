## mpv-config-bundle

> 配置使用[JiayuYangX/mpv-custom](https://github.com/JiayuYangX/mpv-custom)的个人配置文件
> 
> 采用 [ModernZ](https://github.com/Samillion/ModernZ) 作为 OSC
> 
> 脚本和设置参考自 [mpv-config](https://github.com/dyphire/mpv-config)
> 
> 滤镜和着色器来源于 [mpv_PlayKit（原 mpv-lazy）](https://github.com/hooke007/mpv_PlayKit)
>
> AI字幕生成建议使用[Faster-Whisper-XXL](https://github.com/Purfview/whisper-standalone-win) 放置于mpv.exe同目录(需配置参数)。推荐使用 whisper-ja-1.5B-ct2 放置于``_models``文件夹。

## GitHub 自动构建

本仓库通过 GitHub Actions 自动构建便携式 mpv 播放器整合包，包含：

- **mpv** — [zhongfly_mpv](https://github.com/zhongfly/mpv-winbuild) 每日构建版
- **FFmpeg** — 同源的 ffmpeg.exe
- **yt-dlp** — 最新版 yt-dlp.exe



## mpv 客户端

- [mpv 官网](https://mpv.io/installation) — 第三方编译版列表
  - [dyphire/mpv-winbuild](https://github.com/dyphire/mpv-winbuild/releases) — 含个人补丁的编译版
  - [shinchiro/mpv-winbuild-cmake](https://github.com/shinchiro/mpv-winbuild-cmake/releases) — 标准编译版
  - [zhongfly/mpv-winbuild](https://github.com/zhongfly/mpv-winbuild/releases) — 每日构建版
- [mpv.net](https://github.com/mpvnet-player/mpv.net) — 成熟的 mpv 前端

## 预览
引用自[JiayuYangX/mpv-custom](https://github.com/JiayuYangX/mpv-custom)

 ![1](https://github.com/JiayuYangX/mpv-custom/raw/main/pic1.jpg)


## VapourSynth 滤镜（自行配置）

滤镜文件位于 [~/vs](https://github.com/JiayuYangX/mpv-custom/tree/main/vs) 目录。须配合 mpv_PlayKit 的 vsNV 补丁包使用（下载链接：<https://github.com/hooke007/mpv_PlayKit/releases>）。

### 配置方案一

直接解压 vsNV 补丁包到播放器根目录，已内置 Python 运行环境和 VapourSynth 及其必要插件

### 配置方案二

1. 自行安装 [Python](https://www.python.org) 和 [VapourSynth](https://www.vapoursynth.com/)
2. 安装 [k7sfunc](https://pypi.org/project/k7sfunc/) `pip install k7sfunc`
3. 将 vsNV 补丁包里 vs-plugins 中的所有文件解压到 VapourSynth 安装目录下的 plugins 文件夹中

### 配置方案三

直接下载我使用actions打包的[vsNV为整合包 ](https://github.com/Sereinfy/mpv-config/releases) 多分卷一起下载完成后解压。
