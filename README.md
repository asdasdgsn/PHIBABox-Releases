# PHIBABox 版本发布

这是 PHIBABox 的公开更新渠道，仅存放安装包、更新说明与更新索引，不包含应用源码。

## 安装和更新

最新版本为 [PHIBABox 0.2.0](https://github.com/asdasdgsn/PHIBABox-Releases/releases/tag/v0.2.0)，适用 Apple Silicon，macOS 12.0 及以上。

已有带更新功能的客户端，可在“设置 → 版本更新 → 检查更新”下载安装。首次安装可从 Releases 下载 ZIP，解压后将 PHIBABox.app 放入“应用程序”。不含更新功能的旧版需要先手动安装一次。

浏览器采集插件已内置于 App：在“设置 → 浏览器采集”点击“安装插件”，导出并按弹出的教程在 Chrome / Edge 加载；浏览器扩展更新仍需手动加载新版。

## 自分发更新

安装包通过 HTTPS 下载，并由 Sparkle Ed25519 签名验证，使用同一受信任公钥。应用及嵌入组件使用本地 ad-hoc 签名，不依赖 Apple Developer ID 和 Apple 公证。

此版本未经 Apple 公证，首次安装或部分系统环境可能需要在系统设置中手动允许打开。不改变或关闭系统安全设置。资料库与 Eagle 原文件不包含在更新包内。

`appcast.xml` 是客户端使用的更新索引；更新包验证后才推进索引，已发布资产不会覆盖。
