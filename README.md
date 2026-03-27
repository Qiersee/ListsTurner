# ListsTurner
A local-first, user-controlled music sync tool with optional AI enhancement.  
一个本地优先、用户可控、可选 AI 增强的多平台音乐同步工具。
# 🎵 ListsTurner

<p align="center">
  <b>Turn your music lists across platforms.</b><br>
  让你的音乐列表跨越平台自由流转。
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-planning%20%2F%20early--development-orange" alt="status">
  <img src="https://img.shields.io/badge/platform-Windows-blue" alt="platform">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="license">
  <img src="https://img.shields.io/badge/AI-optional-lightgrey" alt="AI optional">
</p>

> 🚧 **Early-stage project under active planning and development.**  
> 🚧 **项目目前仍处于规划 / 早期开发阶段，我们已在本地确保核心功能可用，但进阶的功能仍在开发。**

---

## ✨ Overview | 项目简介

**ListsTurner** is a local-first, user-controlled music sync tool designed to help users move and sync their music lists across different platforms.

**ListsTurner** 是一个**本地优先、用户可控**的音乐列表同步工具，目标是帮助用户在不同音乐平台之间迁移和同步自己的音乐列表。

---
## 🤔 Reason | 此项目是为了什么？

This project originates from a personal need to sync music playlists across platforms.  
However, most existing tools are either paid, or free but not sufficiently complete or reliable.

本项目源于个人在不同音乐平台之间同步歌单的需求。  
然而，现有的大多数工具需要付费，或免费的方案还不够完善或稳定。

We aim to build a tool that is free, reliable, and genuinely user-friendly to address this problem.

我们希望提供一个免费、可靠且真正好用的工具来解决这一问题。

---

## 💸 About Cost & Pricing | 关于费用

Some features (such as AI services or optional cloud capabilities) may involve real operational costs.

部分功能（如 AI 服务或可选云功能）可能会产生实际运行成本。

If any paid options are introduced in the future, they will be strictly used to cover these costs, rather than for profit.

如果未来引入付费选项，其目的仅用于覆盖相关成本，而非盈利。

Users will always have the option to use their own API or rely on local functionality without being forced into paid services.

用户始终可以选择使用自己的 API，或仅使用本地功能，而不会被强制使用付费服务。

---

## 🎯 Project Goals | 项目目标

ListsTurner aims to become a tool that:

ListsTurner 希望成为这样一个工具：

- Syncs music lists across platforms  
  在不同音乐平台之间同步音乐列表

- Starts from “liked songs / favorite songs” and expands in the future  
  从“喜欢的音乐 / 收藏歌曲”开始，未来再逐步扩展

- Uses **rules first**, with **optional AI enhancement** for difficult matches  
  以**规则匹配优先**，并在复杂情况下提供**可选 AI 增强修正**

- Keeps users in control of their data, API usage, and optional cloud features  
  让用户始终掌控自己的数据、API 使用方式以及是否启用云功能

- Stays lightweight, transparent, and easy to opt out from  
  保持轻量、透明，并且随时可以退出或停用增强功能

---

## 🚧 Current Status | 当前状态

This repository is currently in the **planning / early development** stage.

当前仓库仍处于**规划 / 早期开发**阶段。

At this moment:

目前：

- The project direction and feature boundaries are being defined  
  项目方向和功能边界正在整理中

- The core architecture is being designed  
  核心架构正在设计中

- README and roadmap are being prepared first  
  README 与路线图正在优先完善

- Production-ready features are **not available yet**  
  **暂时还没有可直接使用的正式功能**

## 🗓️ Release Plan | 发布计划

The first version of this project is planned to be released before September 2026, followed by continuous updates and improvements.

本项目预计将在 2026 年 9 月之前发布第一个版本，并在此之后持续进行更新与改进。

The README will be updated accordingly as the project evolves.

随着项目的推进，README 内容也会持续更新与完善。

---

## 🧩 Initial Scope | 初始范围

The first practical target of ListsTurner is:

ListsTurner 的第一个实际目标是：

- **YouTube Music**
- **NetEase Cloud Music（网易云音乐）**

And the first sync scope will focus on:

最开始的同步范围将聚焦于：

- **Liked / favorite songs**
- **Only syncing additions**
- **No automatic scheduled sync in the earliest version**

也就是：

- **“喜欢的音乐 / 收藏歌曲”**
- **初期只同步新增项**
- **最早版本暂不追求自动定时同步**

---

## ✨ Planned Features | 计划中的功能

> The items below are **project plans**, not promises of current availability.  
> 以下内容是**项目计划**，并不代表当前已经全部可用。

### Core Features | 核心功能
- Cross-platform music list syncing  
  跨平台音乐列表同步

- Local-first desktop experience  
  本地优先的桌面工具体验

- Rule-based song matching  
  基于规则的歌曲匹配

- Sync history and rollback support  
  同步历史记录与回滚支持

### Optional AI Enhancement | 可选 AI 增强
- AI-assisted song correction for difficult matches  
  在复杂匹配场景下使用 AI 进行辅助修正

- User-provided API key support  
  支持用户自行提供 API Key

- Optional built-in paid API path for users who prefer convenience  
  为不想折腾配置的用户提供可选的内置付费 API 路径

- Full-playlist deep correction mode as an advanced option  
  提供“全量歌单深度校准”这样的高级选项

### Optional Cloud Features | 可选云功能
- Cross-device sync for selected records / history  
  选定记录与历史数据的跨设备同步

- Shared mapping cache to reduce repeated AI cost  
  共享匹配缓存，以减少重复 AI 消耗

- Low-profile account system hidden in settings  
  低存在感的账号系统，隐藏于设置中

---

## 🧠 Design Principles | 设计原则

ListsTurner is not meant to become a bloated platform.

ListsTurner 不希望变成一个臃肿的平台。

It is being designed around these principles:

它会尽量遵循这些原则：

### 1. Local-first | 本地优先
Core syncing logic should work locally whenever possible.  
核心同步逻辑尽量本地完成。

### 2. User-controlled | 用户可控
AI, cloud, and account features should all be optional.  
AI、云功能、账号系统都应该是可选的。

### 3. Transparent cost | 成本透明
Any resource-heavy feature should clearly explain extra cost before running.  
任何高资源消耗功能，都应在执行前明确告知额外成本。

### 4. Reversible actions | 可反悔
Users should have history records, export ability, and rollback support whenever possible.  
尽量为用户提供历史记录、导出能力和回滚支持。

### 5. Clean experience | 干净的体验
The tool should stay simple by default, with advanced features tucked away instead of forcing themselves into the main flow.  
默认界面应尽量简洁，高级功能应隐藏在合适的位置，而不是侵入主流程。

### 6. Open and replaceable | 开放且可替代
Users should not be locked into the developer’s cloud or API service.  
用户不应被锁死在开发者提供的云服务或 API 上。

---

## 🤖 About AI | 关于 AI

AI is planned as an **optional second-layer correction mechanism**, not the foundation of the tool.

AI 被规划为**可选的二级修正机制**，而不是这个工具的基础依赖。

The intended logic is:

预期逻辑是：

1. Try rule-based matching first  
   优先进行规则匹配

2. Only use AI when necessary  
   仅在必要时使用 AI

3. Let users choose how AI is provided  
   由用户自行决定 AI 的来源

Possible future AI modes:

未来可能支持的 AI 模式：

- **Use your own API key**  
  **使用用户自己的 API Key**

- **Use developer-provided API service**  
  **使用开发者提供的 API 服务**

- **Advanced full-list correction**  
  **高级全量歌单校准**

AI should improve accuracy, but it should never become a forced dependency.

AI 应该提升准确率，但不应成为强制依赖。

---

## ☁️ About Cloud & Accounts | 关于云功能与账号

Cloud features are planned as **optional enhancements**, not hard requirements.

云功能会被设计为**可选增强项**，而不是硬性要求。

Possible future use cases include:

未来可能用途包括：

- Syncing selected history records across devices  
  跨设备同步部分历史记录

- Reusing previously verified matches  
  复用已验证的匹配结果

- Saving users AI cost through shared mapping cache  
  通过共享映射缓存为用户节省 AI 成本

The account system, if introduced, should stay low-profile and hidden in settings unless explicitly needed.

如果将来加入账号系统，也会尽量保持低存在感，藏在设置中，仅在用户需要时出现。

---

## 🔐 Data & Privacy | 数据与隐私

ListsTurner is intended to respect the following ideas:

ListsTurner 希望遵循以下数据与隐私原则：

- Local data should remain local by default  
  本地数据默认只保存在本地

- Cloud upload should require explicit user consent  
  上传云端应要求用户明确同意

- Users should be able to export important data  
  用户应能够导出重要数据

- Optional services should never trap users  
  可选服务不应让用户被“锁死”

Even if optional cloud features are ever discontinued in the future, the goal is to keep the core local tool usable.

即使未来可选云服务停止，目标也应是保证核心本地工具仍然可用。

---

## 🛣️ Roadmap | 路线图

### Phase 1 | 第一阶段
- Define project architecture  
  明确项目架构

- Build the desktop GUI skeleton  
  搭建桌面 GUI 骨架

- Implement basic platform connection flow  
  实现基础平台连接流程

### Phase 2 | 第二阶段
- Read music lists from supported platforms  
  读取已支持平台的音乐列表

- Implement rule-based matching  
  实现规则匹配

- Support first sync flow  
  支持第一版同步流程

### Phase 3 | 第三阶段
- Add history records and rollback  
  增加历史记录与回滚

- Add optional AI correction  
  增加可选 AI 修正

- Improve UX and settings structure  
  优化交互与设置结构

### Phase 4 | 第四阶段
- Explore optional cloud sync and shared cache  
  探索可选云同步与共享缓存

- Expand support for more platforms  
  扩展更多平台支持

---

## 🔮 Future Plans | 未来计划

In the long run, ListsTurner may expand to support more music platforms, for example:

长期来看，ListsTurner 希望支持更多音乐平台，例如：

- Spotify
- Apple Music
- QQ Music（QQ 音乐）
- More platforms if suitable APIs / approaches are available  
  以及其他在条件允许时可接入的平台

But this is a direction, not a guarantee of immediate implementation.

不过这代表的是未来方向，并不意味着会立刻实现。
