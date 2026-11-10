---
layout: "customer-mashuyun-20261110-r1"
title: 麻树云客户部署
permalink: "/versions/mashuyun-20261110-r1/"
release_id: "mashuyun-20261110-r1"
---
# 麻树云客户部署

在麻树云完成注册、验证邮箱和开通组织后，可以把构建与文件服务部署到自己的机器。安装包、附件、源码凭据和应用签名材料保留在客户侧。

[打开麻树云控制台](https://mashu.yuyuntu.cn)，注册或登录后进入当前组织的客户节点引导。

当前文档对应 **mashuyun-20261110-r1**。下载时请以登录平台显示的批准版本和目标机器平台为准。

## 选择部署方式

| 方式 | 机器安排 | 适合的使用场景 |
| --- | --- | --- |
| [同机部署]({{ '/versions/mashuyun-20261110-r1/combined/' | relative_url }}) | 一台机器同时运行构建与文件服务 | 从一台 Mac 或 Linux 构建机开始使用 |
| [分机部署]({{ '/versions/mashuyun-20261110-r1/split/' | relative_url }}) | 先安装文件机，再接入构建机 | 构建机与文件存储分开放置 |
| [仅文件服务]({{ '/versions/mashuyun-20261110-r1/fileservice/' | relative_url }}) | 只安装文件机 | 已有安装包，需要上传、发布和下载 |

## 从注册到完成验证

1. [快速开始]({{ '/versions/mashuyun-20261110-r1/quick-start/' | relative_url }})：注册组织，进入客户节点引导。
2. [环境准备]({{ '/versions/mashuyun-20261110-r1/requirements/' | relative_url }})：确认机器、存储、网络和证书。
3. [可信下载]({{ '/versions/mashuyun-20261110-r1/downloads/' | relative_url }})：下载本组织配置，核验工具与节点包。
4. 按所选部署方式完成登记、自动授权和服务检查，再验证真实安装包的发布与完整下载。

安装器显示服务检查完成后，还需要回到平台完成业务验证。Agent 在线、打开下载页面或保存验证范围，都不能代替完整下载及摘要校验。

遇到中断、证书或授权问题时，按[维护与恢复]({{ '/versions/mashuyun-20261110-r1/maintenance/' | relative_url }})沿原机器和原安装目录继续。
