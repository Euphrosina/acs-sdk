# ACS SDK Components

Android Code Studio SDK 组件分发仓库。

## 内容
- `manifest.json` — 安装器组件清单（sha256 校验）
- Release `sdk3637` — build-tools 35.0.1 / 36.1.0 / 37.0.0 arm64 自组包 + platform 35/36/37

## 组包策略
- `aapt2` — ReVanced 社区维护的 AOSP 主线静态编译版（NDK r27c，arm64/armv7）
- `d8` / `apksigner` 等 — Google 官方 build-tools zip 的 Java 组件（平台无关）
- platform — Google 官方 platform zip（平台无关）

## 校验
所有包均带 sha256，安装器下载后强制校验。
