# 离线AI随声译 · 安装包下载

作者：alexwuhao 制作 · alexwuhao@163.com

本仓库用于公开分发 Android APK、安装说明和校验文件。源码单独维护在私有仓库。

## v0.2.0 多语言调试版

**[下载 Android APK](https://github.com/alexwuhao2001-gif/offline-ai-suishengyi-downloads/releases/download/v0.2.0/offline-ai-suishengyi-v0.2.0-debug.apk)**（约78 MiB，无需登录）

[查看版本说明与所有附件](https://github.com/alexwuhao2001-gif/offline-ai-suishengyi-downloads/releases/tag/v0.2.0)

### 安装

下载 APK 后安装。已有第一版可直接覆盖安装，请勿先卸载，否则手机中已导入的模型和历史会被删除。首次安装需要允许对应来源安装应用。

APK不包含大模型。首次使用须在应用的“设置→模型与离线资源”中准备Hy-MT2翻译模型和所需语音资源；安装资源后可断网使用。已有资源可以继续使用。

### 功能与测试范围

- 指定20种语言可独立选择输入和目标语言，默认中文→英文。
- 持续收音，默认静音2秒后分段，可选3秒；连续记录面板，底部按钮固定。
- 启动自动加载已有翻译模型。
- 新增Whisper通用包和粤语增强包入口，按需安装。

这是调试预发布版。10项单元测试和13项Android 15 x86_64模拟器离线测试通过；用户手机延迟、发热以及非英语识音准确率仍需实际验证。译音需要系统已有对应语言的离线TTS语音；收音语言需手动切换，切换应用或锁屏会停止收音。

### APK SHA-256

```text
a7cf94f7df7bafcbda19233eb36c382ac571b2e92f7a5c7cbb1f5604ca521be4
```