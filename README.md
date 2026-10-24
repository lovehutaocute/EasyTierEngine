# EasyTierEngine

Minexa（Android 手机开 MC 服务器的 App）的 **EasyTier 组网引擎**分发仓库。

引擎按需下载，不打进 APK —— 减小安装包体积，也避免进入系统 16KB 页对齐扫描清单。

## 下载

| 版本 | 文件 | 说明 |
|---|---|---|
| v2.7.0 | [libeasytier_android_jni.so](../../releases/download/v2.7.0/libeasytier_android_jni.so) | arm64-v8a，16,411,848 字节 |

GitHub 直连不畅时可用加速镜像，例如：

```
https://ghfast.top/https://github.com/lovehutaocute/EasyTierEngine/releases/download/v2.7.0/libeasytier_android_jni.so
```

## 校验

```
SHA-256 (libeasytier_android_jni.so) = 7fb3e098d55b93c80fc19e15b364d69d69ba16ba998c53fcfd772366ad176d81
```

完整清单见各 Release 附带的 checksums.txt。Minexa 客户端下载后会自动校验大小与指纹。

## 来源与协议

- 构建：EasyTier/EasyTier `v2.7.0` 的 `easytier-android-jni`（CI 构建，产物未做任何修改）
- 上游协议：**LGPL-3.0** —— 本仓库仅分发构建产物，源码与修改说明见上游仓库
