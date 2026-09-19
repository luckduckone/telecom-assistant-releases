# 电信助手 · 客户端下载

校园电信助手 App 客户端发布仓库。所有安装包都在 [Releases](https://github.com/luckduckone/telecom-assistant-releases/releases) 页面,**无需登录 GitHub 即可直接下载**。

> **本项目不开源。** 本仓库仅提供已打包的客户端安装包,不含、不提供任何源码(客户端与服务器端均不提供),详见下方[闭源声明](#️-闭源声明)。

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
2. 用自签工具重签后安装:爱思助手 / Sideloadly / AltStore(个人 Apple ID 即可)。**注意:主 App、Frameworks、小组件 appex 必须全量重签,缺一即闪退**;
3. 设置 → 通用 → VPN与设备管理 中信任开发者证书。

## 🗂 历史版本与校验

- 全部历史版本见 [Releases](https://github.com/luckduckone/telecom-assistant-releases/releases) 页面;
- 每个版本 Release 说明中附有 APK / IPA 的 **sha256 校验值**与 build 号,下载后可自行核对。

## ⚠️ 闭源声明

- 本项目**不开源**:本仓库仅分发已编译的客户端安装包,**不含、不提供任何源码**(客户端与服务器端源码均不提供);
- 下载本仓库的任何文件**不授予**源码获取、复制、修改的权利;
- 未经作者书面授权,禁止对本仓库提供的安装包进行反编译、逆向工程、二次打包、再分发或用于商业用途;
- 使用问题(服务器地址、账号开通等)请联系管理员。
