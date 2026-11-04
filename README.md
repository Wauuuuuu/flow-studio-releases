# Flow Studio · 桌面应用下载与更新

本仓库用于公开安装包、版本说明、SHA-256 校验与签名更新清单分发。

## 下载

请进入 [Releases](https://github.com/Wauuuuuu/flow-studio-releases/releases/latest) 下载最新正式版本。Mac 选择 arm64 DMG，Windows 选择 x64 Setup；ZIP 需完整解压后运行。

2.5.20「Luna」已正式发布：素材准备节点的检索规划、素材相关性筛选、口播与逐镜头脚本统一使用节点自己选择的文本模型，不再固定委派 Gemini；选择 Claude 时自动走 Anthropic 原生协议。同时修正 GPT 6.1 Terra 被错标为 GPT 6.1 Sol 的显示问题。本版包含 2.5.19 的默认模型下拉收敛、保存接入 400 修复与不受支持音频模型清理。画布、素材及 API 配置继续保存在本机。

## 更新与校验

Home → 设置 → 软件更新。接通版支持后台检查和下载，校验通过后在下次启动安装。自动更新清单为 Release 内的 `latest.json`（仓库根同名文件保持同步），安装包需通过 Ed25519 签名、大小与 SHA-256 验证。

本产品目前使用开发签名：macOS 尚未完成 Developer ID 签名与公证，Windows 真机安装运行仍待验证。

本仓库不是源码开源仓库，不存放用户数据、API Key 或签名私钥。
