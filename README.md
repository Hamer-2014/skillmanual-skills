# 内链内容建设

`seo-link-neilian` 是一个用于规划 SEO 内链内容的 Skill。它要求先明确页面在主题集群中的角色，再确定页面之间的链接关系与下一步转化路径。

## 内容模型

采用三层结构：

- Core / Conversion Hub：产品页、工具页或主要转化页，承接商业意图。
- Topic Pillar：主题指南或分类指南，组织一个主题并支撑多个长尾页面。
- Long-tail Support：教程、对比、清单或场景文章，回答具体问题并向上链接到主题页。

## 使用规则

每个新页面都先完成 Content Brief，再开始写作。Brief 至少要包含：

- 页面层级、主关键词、搜索意图和稳定 URL
- 父页面
- 至少两个有用的相关页面
- CTA 目标
- 独特价值

正文应同时规划向上链接、横向链接和转化链接，并使用自然且有变化的锚文本。缺少父页面、两个相关页面、CTA 或独特价值时，应先重做内容计划，不直接发布文章。

## 目录结构

```text
skills/
└── seo-link-neilian/
    ├── SKILL.md
    └── agents/
        └── openai.yaml
```

## 安装

以下步骤适用于尚未安装该 Skill 的项目。先进入目标项目目录，在 Windows PowerShell 中运行：

```powershell
git clone -c core.autocrlf=false https://github.com/Hamer-2014/skillmanual-skills.git
git -C skillmanual-skills checkout --detach 0a78f329cf69c87a5dc795335f94155f7f44d20b
New-Item -ItemType Directory -Force .agents/skills | Out-Null
Copy-Item -LiteralPath skillmanual-skills/skills/seo-link-neilian -Destination .agents/skills/seo-link-neilian -Recurse
```

项目级安装目录为 `.agents/skills/seo-link-neilian`，符合 [Codex 官方 Skill 文档](https://learn.chatgpt.com/docs/build-skills) 的仓库发现路径。保留宿主已有的禁用规则和显式调用策略。`core.autocrlf=false` 让这个新 clone 保持发布版文件字节，便于核对 SHA256，不修改全局 Git 配置。

2026-10-08 在全新 Windows 目录完成固定版本 checkout、目录安装及两个文件的原始字节哈希验证。当前已安装 CLI 为 `0.154.0`；本轮 CLI 自动发现、实际调用与同输入对照仍待账号登录，尚未完成。桌面 App 的当前观察版本为 `26.1002.52244`（build `13536`），该版本号不等于 CLI 版本或模型版本。

网站记录：[中文详情](https://skillmanual.com/zh/skills/6c14f465-1e14-4f94-8498-a499b32f1e1c) · [English](https://skillmanual.com/skills/6c14f465-1e14-4f94-8498-a499b32f1e1c)。报告为编辑自测和部分验证，不是独立审核、所有宿主兼容或搜索排名保证。

## 调用

在 Codex 会话中调用：

```text
$seo-link-neilian
```

本包不包含执行脚本、服务账号配置或付费 API 代码。本说明不宣称已完成全部宿主的兼容实测，也不保证 SEO 排名或运行效果。Skill 文件的获取方式与宿主、模型及外部服务的运行费用相互独立，实际费用取决于所使用的宿主和服务方案。

## English

`seo-link-neilian` is an internal-linking content planning skill. It uses a three-layer content model, requires a complete Content Brief before writing, and expects a parent page, at least two related pages, a CTA, and unique value for every new page. The package contains guidance only: no execution scripts, service-account configuration, or paid API code. Host compatibility, model costs, and external service costs depend on the host and plan in use; this README makes no ranking or testing guarantee.

## 许可

本仓库以 [MIT License](LICENSE) 发布。再分发时请保留版权和许可声明。
