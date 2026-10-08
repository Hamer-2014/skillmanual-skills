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

```text
git clone https://github.com/Hamer-2014/skillmanual-skills.git
```

将 `skills/seo-link-neilian` 整个目录放入实际宿主的 Skill 目录。Codex 可使用 `$CODEX_HOME/skills`；未设置时通常为 `~/.codex/skills`。请保留宿主已有的禁用规则和显式调用策略。本说明不承诺 Claude 或其他具体宿主可以自动安装，也不建议通过包管理器自动执行安装命令。

## 调用

```text
$seo-link-neilian
```

本包不包含执行脚本、服务账号配置或付费 API 代码。本说明不宣称已完成全部宿主的兼容实测，也不保证 SEO 排名或运行效果。Skill 文件的获取方式与宿主、模型及外部服务的运行费用相互独立，实际费用取决于所使用的宿主和服务方案。

## English

`seo-link-neilian` is an internal-linking content planning skill. It uses a three-layer content model, requires a complete Content Brief before writing, and expects a parent page, at least two related pages, a CTA, and unique value for every new page. The package contains guidance only: no execution scripts, service-account configuration, or paid API code. Host compatibility, model costs, and external service costs depend on the host and plan in use; this README makes no ranking or testing guarantee.

## 许可

本仓库以 [MIT License](LICENSE) 发布。再分发时请保留版权和许可声明。
