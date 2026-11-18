# DS Always 安装包

这里只放 DS Always 的 Windows 安装包与自动更新清单（`latest.yml` / `.blockmap`），源码在公开仓库
[kayz/dsalways](https://github.com/kayz/dsalways)。

## 下载最新版本

**→ [最新版本下载页](https://github.com/kayz/dsalways-releases/releases/latest)**

也可以点页面右侧 Releases 区块里标着 `Latest` 的那一条。始终以 `/releases/latest` 为准，不要直接下旧 tag 里的包。

当前版本 **1.3.0**：

| 文件 | 适合谁 | 自动更新 |
| --- | --- | --- |
| `DS-Always-Setup-1.3.0.exe` | 常规使用，推荐 | 支持，应用内一键升级 |
| `DS-Always-Portable-1.3.0.exe` | 免安装、可放 U 盘带走 | 不支持，需手动换新包 |

安装版装到 `%LOCALAPPDATA%\Programs\DSAlways`。未做代码签名，首次运行 Windows SmartScreen
可能提示「未知发布者」，点「更多信息 → 仍要运行」即可。macOS / Linux 请从源码构建。

项目介绍、中文使用说明与源码运行方式见 [kayz/dsalways](https://github.com/kayz/dsalways) 的 README。
