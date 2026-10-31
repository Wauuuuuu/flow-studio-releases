# Flow Studio · 桌面应用下载与更新

本仓库用于公开安装包、版本说明、SHA-256 校验与签名更新清单分发。

## 下载

请进入 [Releases](https://github.com/Wauuuuuu/flow-studio-releases/releases/latest) 下载最新正式版本。Mac 选择 arm64 DMG，Windows 选择 x64 Setup；ZIP 需完整解压后运行。

2.3.4 已正式发布，包含 API 模型目录、自选显示/隐藏、参考与自定义单价和本机费用统计。2.3.1/2.3.2 用户需要手动安装本版一次。画布、素材及 API 配置继续保存在本机。

## 更新与校验

Home → 设置 → 软件更新。接通版支持后台检查和下载，校验通过后在下次启动安装。自动更新清单位于 Releases 的 latest.json，安装包需通过 Ed25519 签名、大小与 SHA-256 验证。

本产品目前使用开发签名：macOS 尚未完成 Developer ID 签名与公证，Windows 真机安装运行仍待验证。

本仓库不是源码开源仓库，不存放用户数据、API Key 或签名私钥。
