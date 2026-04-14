# Bitwarden LoongArch64 Binaries

[English](./README_en.md)

使用 GitHub Actions 构建 Bitwarden Desktop 的 LoongArch64 原生模块。

## 使用方法

在 GitHub Actions 中手动触发 `Build Loongarch64 Binaries` 工作流，传入 `tag` 参数指定要构建的 Bitwarden 版本标签（如 `desktop-v2024.12.0`）。

构建产物：
- `desktop_napi.linux-loong64-gnu.node`
- `desktop_proxy`
- `libprocess_isolation.so`

## 相关项目

- [bitwarden/clients](https://github.com/bitwarden/clients) - Bitwarden 官方客户端
