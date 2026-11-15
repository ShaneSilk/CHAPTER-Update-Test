# CHAPTER · 独立更新测试

本仓库仅供 CHAPTER 自动更新验收，不是日常使用版。日常安装请访问 [CHAPTER-Releases](https://github.com/ShaneSilk/CHAPTER-Releases/releases)。

测试安装版使用独立产品标识和 `%APPDATA%\CHAPTER Update Test` 数据目录，不能与正式版本混用。本次 0.2.0 与 0.2.1 基于同一受测源码，以版本差异验收线上发现、下载、取消、安装、自动重启及合成存档和附件保留。

仓库只包含公开说明、测试安装程序和签名更新清单，不包含源码、真实用户数据或凭据。测试使用独立的 Ed25519 签名密钥，正式版不会接受本仓库更新。