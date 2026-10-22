# 视频发布工作台 · 安装包下载

[**打开 v0.1.0 下载页面**](https://github.com/qijv/local-video-publisher-releases/releases/tag/v0.1.0)

本仓库仅提供安装包、使用说明与文件校验值，不包含应用源码。无需注册或登录 GitHub 即可下载。

本地视频发布工具第一版，先支持快手。选择视频、粘贴格式化文案、选择账号后，APP 自动上传并填写，最终发布由本人在官方网页确认。

## 下载安装

- [**Windows 10 / 11（64 位）· 下载 EXE**](https://github.com/qijv/local-video-publisher-releases/releases/download/v0.1.0/LocalVideoPublisher_0.1.0_Windows_x64_setup.exe)：双击安装。缺少 WebView2 时安装器联网补齐，无需 Chrome。
- [**Mac（macOS 14+）· 下载 DMG**](https://github.com/qijv/local-video-publisher-releases/releases/download/v0.1.0/LocalVideoPublisher_0.1.0_macOS_universal.dmg)：打开后将 APP 拖到“应用程序”，同时支持 Apple 芯片和 Intel。
- `SHA256SUMS.txt` 提供三个安装资产的校验值；`BUILD-INFO.txt` 提供版本与构建提交标识。安装包不包含开发者的账号、登录资料或测试视频。

当前为无付费证书的体验包：Mac 使用临时签名，未通过 Apple 公证；Windows 未进行发行商代码签名。系统可能提示来源未验证。Mac 可在“系统设置 → 隐私与安全性”确认打开；Windows 请核对来源后运行。

## 首次体验

1. 在 APP 右上角添加快手账号，在 APP 内扫码并确认登录。登录资料只保存在自己的电脑上。
2. 选择短测试视频，粘贴并解析文案；也可打开“提示词助手”，复制模板给外部 AI 使用。
3. 点击“检查并开始”，检查视频预览、文案和话题。**体验验证时不要点击官方网页的“发布”按钮。**

Mac 的实际账号上传、文案和两个话题已验证；Windows 的真实账号上传与不同用户电脑上的安装兼容性仍需体验验收。自动构建及无账号启动检查不代替真实账号验证。找不到唯一匹配话题时会标记需检查。


GitHub 自动生成的 Source code ZIP/TAR 仅包含本下载仓库的说明文件，不是应用源码。
