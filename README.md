# 电信助手 · 客户端下载

校园电信助手 App 客户端发布仓库。所有安装包都在 [Releases](https://github.com/luckduckone/telecom-assistant-releases/releases) 页面,**无需登录 GitHub 即可直接下载**。

## 📲 最新版直链(永久有效,始终指向最新发布)

| 平台 | 直链 | 说明 |
| --- | --- | --- |
| Android | [`latest.apk`](https://github.com/luckduckone/telecom-assistant-releases/releases/latest/download/latest.apk) | 下载后直接安装 |
| iOS | [`latest.ipa`](https://github.com/luckduckone/telecom-assistant-releases/releases/latest/download/latest.ipa) | **未签名**,需重签后安装(见下) |

也可以打开 [最新版 Release 页](https://github.com/luckduckone/telecom-assistant-releases/releases/latest) 下载带版本号的文件(`telecom-assistant-vX.X.X-release.apk` / `telecom-assistant-vX.X.X-unsigned.ipa`)。

## 📱 安装说明

### Android

1. 下载 `latest.apk`(或任意版本的 `telecom-assistant-vX.X.X-release.apk`);
2. 允许「安装未知来源应用」后直接安装。

### iOS(IPA 未签名,必须自签)

1. 下载 `latest.ipa`;
2. 用自签工具重签后安装,任选其一:
   - 爱思助手 / Sideloadly / AltStore(个人 Apple ID 即可);
   - 有证书的用户:下载该版本附件中的 `package-sign-ipa.sh`、`verify-signature.sh`,按脚本内注释全量重签(**小组件必须全量签名,否则闪退**)。
3. 设置 → 通用 → VPN与设备管理 中信任开发者证书。

## 🗂 历史版本与校验

- 全部历史版本见 [Releases](https://github.com/luckduckone/telecom-assistant-releases/releases) 页面;
- 每个版本 Release 说明中附有 APK / IPA 的 **sha256 校验值**与 build 号,下载后可自行核对。

## ⚠️ 说明

- 本仓库只存放客户端安装包,**不含任何源码与服务器信息**;
- 使用问题(服务器地址、账号开通等)请联系管理员。
