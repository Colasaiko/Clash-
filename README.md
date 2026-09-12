# 🌐 Clash 新手配置与节点选择 Guide

> **📖 [在线阅读教程](https://colasaiko.github.io/Clash-/)**

本文面向 Clash 初学者，从下载安装到配置订阅，再到节点选择、延迟、丢包、速度和稳定性测试，帮助你建立一套简单、实用的网络优化思路。

## 📖 关于本 Guide

如果你刚开始接触 Clash，不需要一次阅读一篇很长的教程。
本 Guide 将 Clash 的基础知识拆分成多个独立章节，从：
**下载安装到配置 → 节点选择 → 网络测试 → 自动选择 → 进阶使用**
逐步学习。
每个章节都可以独立阅读，也可以按照推荐顺序从头开始。

## 📚 文章目录

### 🟢 第一阶段：Clash 基础
适合第一次接触 Clash 的用户。
- [01-Clash基础配置](./01-Clash基础配置.md)
  > 涵盖内容：Clash 是什么？、下载与安装、配置与订阅导入、节点与代理组认知、系统代理与运行模式。

### 🔵 第二阶段：节点选择
学会基础操作后，可以继续了解如何判断节点质量。
- [02-节点质量判断](./02-节点质量判断.md)
  > 涵盖内容：节点延迟、节点丢包、节点速度、节点稳定性、高峰期节点测试表现。

### 🟣 第三阶段：节点测试与自动选择
进一步学习如何减少手动切换节点。
- [03-实际测试节点](./03-实际测试节点.md)
  > 涵盖内容：综合测试节点、URL-Test 自动选择、Fallback 故障切换、Load-Balance 负载均衡。

### 🟠 第四阶段：不同场景的节点选择
根据自己的使用需求选择合适的节点。
- [04-新手常见误区](./04-新手常见误区.md)
  > 涵盖内容：日常网页浏览、视频与流媒体、AI 与在线工具、实时互动应用、跨地区办公场景及新手常见误区。

### 🔴 第五阶段：推荐工具与进阶学习
完成基础学习后，可以继续了解：
- [05-推荐工具](./05-推荐工具.md)
  > 涵盖内容：必备工具资源（Clash Verge Rev, Mihomo 文档等）、总结挑选节点的思路，以及规则分流、DNS、TUN 模式等进阶方向的指引。

## 🧭 推荐学习顺序

如果你是完全的新手，推荐按照下面的顺序阅读：

**Clash 是什么？** ↓ **下载安装** ↓ **导入配置** ↓ **认识节点** ↓ **开启系统代理** ↓ **了解 Rule 模式** ↓ **学习延迟** ↓ **学习丢包** ↓ **学习速度** ↓ **学习稳定性** ↓ **学会测试节点** ↓ **了解 URL-Test** ↓ **了解 Fallback** ↓ **根据使用场景选择节点** ↓ **规则 / DNS / TUN** ↓ **进阶配置**

如果你已经会使用 Clash，可以直接跳到自己需要的章节。

## 🛠️ 推荐工具

以下工具可以辅助学习和测试。

### Clash Verge Rev
- 官方 GitHub：[https://github.com/Clash-Verge-rev/clash-verge-rev](https://github.com/Clash-Verge-rev/clash-verge-rev)
- Releases：[https://github.com/Clash-Verge-rev/clash-verge-rev/releases](https://github.com/Clash-Verge-rev/clash-verge-rev/releases)

### Mihomo
- 官方文档：[https://wiki.metacubex.one/](https://wiki.metacubex.one/)
- 代理组：[https://wiki.metacubex.one/en/config/proxy-groups/](https://wiki.metacubex.one/en/config/proxy-groups/)
- 节点：[https://wiki.metacubex.one/en/config/proxies/](https://wiki.metacubex.one/en/config/proxies/)
- API：[https://wiki.metacubex.one/en/api/](https://wiki.metacubex.one/en/api/)

### IPinfo
用于查看公网 IP 及相关网络信息：
[https://ipinfo.io/](https://ipinfo.io/)

### Cloudflare Speed Test
用于进行基础网络测速：
[https://speed.cloudflare.com/](https://speed.cloudflare.com/)

## ❓ 常见问题

**Clash 是什么？**
Clash 是一类网络代理客户端生态的名称，常用于管理代理节点、规则和流量分流。
目前不同项目和客户端可能采用不同内核，例如 Mihomo。

**我完全不会 Clash，应该从哪里开始？**
建议从 `01-Clash基础配置.md` 开始阅读。完成基础配置后，再进入节点测试和进阶部分。

**为什么不把所有内容放在一篇文章里？**
因为完整的 Clash 教程内容较多。
拆分之后：
- 每篇文章更容易阅读
- GitHub 页面更加清晰
- 可以快速找到需要的内容
- 新手不需要一次阅读大量文字
- 后续更新某一个章节也更加方便

## 📌 说明

本文档主要用于 Clash / Mihomo 相关知识学习和网络工具配置参考。
不同客户端、内核和配置文件的功能可能存在差异。
软件版本更新后，界面名称、配置方式和功能细节可能发生变化，请以对应项目的官方文档为准。
请遵守所在地区及相关网络服务的法律法规、平台规则和服务条款，并合理使用网络工具。

## ⭐ 如果这个 Guide 对你有帮助

可以收藏这个仓库，后续按照目录逐步学习。
从基础开始，不需要一次学完所有内容。

*Learn step by step.*
*Understand first, configure second.*
