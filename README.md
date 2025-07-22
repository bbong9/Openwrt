# OpenWrt-Nikki 配置备份 / OpenWrt-Nikki Configuration Backup

此仓库包含自用的 **Nikki 配置文件** 和 **规则**，用于在 OpenWrt 上设置透明代理（Mihomo）。这些配置文件和规则主要用于个人备份，便于快速恢复和管理。  
This repository contains personal **Nikki configuration files** and **rules** for setting up transparent proxy (Mihomo) on OpenWrt. These files and rules are mainly for personal backup, allowing quick restoration and management.

## 内容 / Contents

- **Nikki 配置文件（YAML 格式）**: 包含了针对 Nikki 透明代理的自定义配置。  
  **Nikki Configuration Files (YAML format)**: Custom configurations for Nikki transparent proxy.
- **规则文件**: 一些与 YAML 配置相关的规则，确保代理和访问控制的正常工作。  
  **Rules Files**: Rules related to the YAML configuration, ensuring proper proxy and access control.

## 使用说明 / Usage Instructions

1. 将 YAML 配置文件复制到你的 OpenWrt 设备的适当位置。  
   Copy the YAML configuration files to the appropriate location on your OpenWrt device.
2. 根据需要编辑配置文件，以匹配你的具体环境（例如代理设置、访问控制规则等）。  
   Edit the configuration files as needed to match your specific environment (e.g., proxy settings, access control rules).
3. 使用这些配置文件启动和配置 **Mihomo**，实现透明代理功能。  
   Use these configuration files to start and configure **Mihomo** for transparent proxying.
4. 使用预定义的规则来管理网络流量和访问控制。  
   Use predefined rules to manage network traffic and access control.

## Nikki 安装地址 / Nikki Installation Link

你可以在 [Nikki GitHub 仓库](https://github.com/nikkinikki-org/OpenWrt-nikki/tree/main) 找到有关如何安装和配置 Nikki 的更多信息。  
You can find more information on how to install and configure Nikki in the [Nikki GitHub Repository](https://github.com/nikkinikki-org/OpenWrt-nikki/tree/main).

## 说明 / Notes

- 所有配置文件和规则仅适用于个人备份和自用。  
  All configuration files and rules are for personal backup and use only.
- 本仓库不包括完整的安装步骤或依赖管理，假设用户已具备一定的 OpenWrt 配置经验。  
  This repository does not include full installation steps or dependency management, assuming the user has some experience with OpenWrt configuration.
