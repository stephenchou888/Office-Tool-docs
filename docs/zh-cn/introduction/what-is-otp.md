# 什么是 Office Tool Plus？ {#what-is-office-tool-plus}

Office Tool Plus 是一个强大且实用的 Office 部署工具。

Office Tool Plus 基于 [Office 部署工具](https://aka.ms/ODT)制作，可以很方便的部署 Office，其内置迅雷云加速开放平台和 [Downloader](https://github.com/bezzad/Downloader) 引擎可帮助您更快地下载 Office。你也可以使用 Office Tool Plus 的其他功能、小工具快捷、方便地激活和管理 Office 哦！

支持下列产品：

- Microsoft 365
- Office 2016, 2019, 2021, 2024
- Visio 2016, 2019, 2021, 2024 & Visio Online Plan 2
- Project 2016, 2019, 2021, 2024 & Project Online Desktop Client

无论你是个体还是团队，Office Tool Plus 都是你的得力小助手。

## 功能 {#features}

- 创建 Office 安装配置，支持导出到本地，或从本地或网络位置导入。
- 下载 Office，支持所有通道的 Office，支持所有的 Office 语言。
- 安装 Office，支持对现有的 Office 进行修改，例如产品、语言、应用程序的安装与卸载。
- 创建 Office ISO，支持默认安装配置、静默安装配置、扩展安装脚本。
- 激活 Office，支持在线激活、电话激活、KMS 激活。
- 支持 Office 授权管理，包括许可证管理，密钥管理以及 KMS 管理。
- 修改 Office 更新通道，支持在不重装 Office 的情况下升级/降级 Office.
- 移除 Office，在 Office 无法正常卸载的情况下强制移除 Office，支持 Office 2003 - Office 最新版本。
- 内置 Office 工具箱，包括重置设置，修复安装问题，修复激活问题等。
- 转换 Office 文档，基于 Office COM，稳定、快速、可靠。
- 自定义主题，打造你自己的专属 Office Tool Plus。

::: tip 注意事项

1. Office Tool Plus 只提供激活管理功能，你需要拥有正版许可证才可以激活你的 Office。

:::

## 组件与结构 {#components-and-structure}

``` txt
Office Tool
├── Office Tool Plus.exe (主程序)
├── Office Tool Plus.Console.exe (终端助手)
├── hostfxr.dll (.NET Host)
├── shared (.NET Runtimes)
└── files
    ├── setup.exe (微软 Office 部署工具)
    ├── preferences (Office 应用程序首选项数据，由微软提供)
    └── Thunder (迅雷云加速开放平台相关文件)
```

通常情况下，Office Tool Plus 会自动下载缺失的组件并自动保持其为最新版本。如果某些组件丢失或者无法自动下载，建议重新下载 Office Tool Plus 以解决问题。
