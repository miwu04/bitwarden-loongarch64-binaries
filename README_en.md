# Bitwarden LoongArch64 Binaries

[中文](./README.md)

Build Bitwarden Desktop native modules for LoongArch64 using GitHub Actions.

## Usage

Manually trigger the `Build Loongarch64 Binaries` workflow in GitHub Actions, passing the `tag` parameter to specify the Bitwarden version tag to build (e.g., `desktop-v2024.12.0`).

## Build Artifacts

- `desktop_napi.linux-loong64-gnu.node`
- `desktop_proxy`
- `libprocess_isolation.so`

## Related Projects

- [bitwarden/clients](https://github.com/bitwarden/clients) - Official Bitwarden clients
