# 真果鉴（红果播放修复版）0.2.72+79

本仓库为 [zhoufuweigg/guoapp](https://github.com/zhoufuweigg/guoapp)（开源仓库，其 README 注明源码源自原作者"鱼佬"）的**二创修复版**，主要修复红果站源 CENC 加密内容无法播放的问题。

## 修复内容

- 合并上游官方仓库 [PR #2](https://github.com/zhoufuweigg/guoapp/pull/2)（fengs2021）的修复：将 Android 播放内核回退到 **media_kit / libmpv**，用于解密红果 CENC 加密内容，解决红果站源无法播放问题。
- 版本号：**0.2.72+79**
- 全站源编译（`--all-sources`），所有站源均为真果鉴。

## 安装包下载

| 架构 | 文件 | 适用设备 |
|---|---|---|
| x86_64 | `zhenguojian-0.2.72+79-x86_64.apk` | MuMu 模拟器 |
| arm64-v8a | `zhenguojian-0.2.72+79-arm64-v8a.apk` | 安卓手机 |

可通过 [Releases](https://github.com/xiazzzzzyy/guoapp-redguo-fix/releases) 页面直接下载对应 APK。

## 安装注意事项

- 新 APK 为 **debug 签名**，与旧版真果鉴签名不同，安装前请**先卸载旧版**，否则会因签名冲突导致安装失败。
- 模拟器请选择 x86_64 包，安卓手机请选择 arm64-v8a 包。

## 致谢

感谢上游开源仓库 [zhoufuweigg/guoapp](https://github.com/zhoufuweigg/guoapp)（源码源自原作者"鱼佬"）及 PR #2 作者 fengs2021 的贡献。
