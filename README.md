[English](README.en.md) | [中文](README.md)
# OpenWrt-Nikki 配置备份

此仓库包含自用的 **Nikki 配置文件** 和 **规则**，用于在 OpenWrt 上设置透明代理（Mihomo）。这些配置文件和规则主要用于个人备份，便于快速恢复和管理。

## 内容

- **Nikki 配置文件（YAML 格式）**: 包含了针对 Nikki 透明代理的自定义配置。
- **规则文件**: 一些与 YAML 配置相关的规则，确保代理和访问控制的正常工作。

## 使用说明

1. 将 YAML 配置文件复制到你的 OpenWrt 设备的适当位置。
2. 根据需要编辑配置文件，以匹配你的具体环境（例如代理设置、访问控制规则等）。
3. 使用这些配置文件启动和配置 **Mihomo**，实现透明代理功能。
4. 使用预定义的规则来管理网络流量和访问控制。

## Nikki 安装地址

你可以在 [Nikki GitHub 仓库](https://github.com/nikkinikki-org/OpenWrt-nikki/tree/main) 找到有关如何安装和配置 Nikki 的更多信息。

## 说明

- 所有配置文件和规则仅适用于个人备份和自用。
- 本仓库不包括完整的安装步骤或依赖管理，假设用户已具备一定的 OpenWrt 配置经验。
