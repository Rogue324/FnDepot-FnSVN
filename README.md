# FnSVN 独立应用源

这是由 Rogue324 维护的 FnSVN 外部应用源，适用于支持 V2 外部源的 FnDepot 客户端。

## 添加到 FnDepot

在 FnDepot 的外部应用源设置中添加：

```text
https://github.com/Rogue324/FnDepot-FnSVN
```

也可以使用根目录 `fnpack.json` 的原始 JSON 直链：

```text
https://raw.githubusercontent.com/Rogue324/FnDepot-FnSVN/main/fnpack.json
```

FnSVN 的代码、安装说明、版本发布及问题反馈见 [FnSVN 项目](https://github.com/Rogue324/SVNOnFnos)。ARM64 为实验性支持，不支持 32 位 ARM。

## 更新应用源

每次发布新版本，在 `fnpack.json` 的 `apps.fnsvn.releases` 中添加版本及其各架构安装包的下载地址、文件大小、SHA256 和最低系统版本；已发布的同版本同架构包不应静默替换。应用源不会自动跟随 FnSVN Release 更新。
