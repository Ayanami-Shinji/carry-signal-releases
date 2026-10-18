# Carry Signal 下载

Carry Signal 的客户端安装包与版本说明。源代码保持私有，安装包公开下载；产品服务和执行权限仍需有效授权。

请从 [Releases](https://github.com/Ayanami-Shinji/carry-signal-releases/releases) 选择版本，并核对该版本提供的 SHA-256。

当前为 [v0.1.10 预发布](https://github.com/Ayanami-Shinji/carry-signal-releases/releases/tag/v0.1.10)，用于安装观察，尚未作为正式稳定版开放。生产受控换机和强制更新保持关闭。

| 设备 | 安装包 |
| --- | --- |
| Apple Silicon Mac（M 系列），macOS 15 或更新 | macOS arm64 ZIP |
| Intel Mac，macOS 15 或更新 | macOS x64 ZIP |
| Windows 11，Intel／AMD 64 位 | Windows x64 Setup.exe |

Windows ARM、Linux 和 Universal Mac 包暂不在首发范围。各版本的实际验证范围以该版本说明为准。

## 安装与升级

Mac 解压后将应用放入「应用程序」；Windows 运行对应安装器，默认安装到 `%LOCALAPPDATA%\carry_signal`，不提供安装路径选择，本地数据保存在 `%APPDATA%\Carry Signal` 内。首批包未使用发布者签名／公证，系统可能显示安全提示；请确认下载来源及文件校验值。

升级前先处理进行中的执行与未决事项，再正常退出应用，安装完整新包。升级保留原数据和本机凭据；升级失败时保留原文件及错误信息，勿删除数据目录重新激活。

Windows v0.1.6 的旧登录态未正确保存，升级后需重新登录一次；新版已修复加密保存与正常重开。无需删除本地数据。

## 数据与执行

交易在客户端本地执行，电脑和应用须持续运行。休眠、关机或断网会影响持续执行与风控。

本地迁移使用加密文件，不上传完整工作区到云端，不合并多台设备历史。迁移还须满足服务端交接、旧端可靠停止及新端核对条件；以应用显示的开放状态为准，不支持复制旧目录或清空数据后绕过交接和未决执行。

请勿在公开 Issues 上传迁移包、数据库、密钥、账号凭据或含敏感信息的日志。
