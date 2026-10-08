---
name: seo-link-neilian
description: Use when planning, writing, reviewing, or adding SEO internal-linking content, blog clusters, soft articles, topic clusters, pillar pages, long-tail support pages, content briefs, anchor text, sitemap content, or agent rules for content pages.
---

# Internal Linking Content

## Overview

Use a three-layer internal-linking model so SEO content grows as a topic cluster, not as scattered soft articles. Every new content page must have a role, parent page, related pages, and conversion path before writing begins.

## Core Model

| Layer | Role | Typical Pages | Main Job |
|---|---|---|---|
| Core / Conversion Hub | First layer | Product page, tool page, service page, main landing page | Own the main commercial intent and receive links from content pages |
| Topic Pillar | Second layer | Theme guide, category guide, major use-case page | Build authority around a mid/high-value topic and support multiple long-tail pages |
| Long-tail Support | Third layer | How-to, comparison, checklist, scenario, question article | Answer a specific user need and link upward to a Topic Pillar |

Do not write a page just because a keyword exists. A page is valid only when its search intent, internal-link role, and next step are clear.

## Required Workflow

1. Inventory existing pages first.
   - List title, URL, primary keyword, search intent, current layer, parent page, related pages, and CTA target.
   - Identify duplicate intent before proposing new content.

2. Choose the new page layer.
   - Core: use only for primary commercial pages.
   - Topic Pillar: use for broad themes that can support several long-tail articles.
   - Long-tail Support: use for specific questions, comparisons, scenarios, and checklists.

3. Write a Content Brief before writing the page.

```md
## Content Brief

- Target layer: Core / Topic Pillar / Long-tail Support
- Primary keyword:
- Search intent: Tool / Product / Decision / Comparison / How-to / Inspiration / Problem-solving
- Target URL slug:
- Parent page:
- Related pages:
- CTA target:
- Unique value:
- Reader stage: Awareness / Consideration / Decision
- Required examples or assets:
- Status: Draft / Ready / Published
```

4. Block weak ideas.
   - If `Parent page` is missing, create or choose a parent first.
   - If `Related pages` has fewer than 2 useful pages, the page may become an orphan.
   - If `Unique value` only says "cover keyword", stop and reshape the topic.

5. Write or modify content only after the brief is coherent.
   - Include upward links, lateral links, and a conversion link.
   - Use natural anchor text, not repeated exact-match anchors.
   - Update content indexes, blog lists, sitemap, footer/nav, or tests when the project has them.

## Page Templates

### Topic Pillar

```md
# [Primary Keyword]

Intro:
- Why users search this topic
- How the product/service/tool relates to the topic
- What decision this page helps users make

Sections:
- What it is
- Who it is for
- Main use cases
- How to choose or evaluate
- Common mistakes
- Examples or scenarios
- FAQ

Internal links:
- Core page
- 2-4 related Topic Pillar pages
- 2-5 supporting Long-tail pages
- Conversion CTA
```

### Long-tail Support

```md
# [Specific Question or Long-tail Keyword]

Intro:
- Direct answer to the question
- Key factors that affect the answer

Sections:
- Short answer
- When this applies
- Step-by-step advice
- Recommended options or examples
- Mistakes to avoid
- Related reading
- CTA

Internal links:
- 1 parent Topic Pillar page
- 1 Core page or conversion page
- 1-3 related Long-tail or Topic Pillar pages
```

## Anchor Text Rules

Mix anchor text types:

| Type | Example |
|---|---|
| Exact match | `AI writing tool` |
| Partial match | `write blog posts with AI` |
| Action | `try the tool online` |
| Decision | `compare the best options before choosing` |
| Scenario | `use this checklist before launch` |

Rules:
- Explain why the linked page is useful in the surrounding sentence.
- Avoid using the same exact-match anchor everywhere.
- Avoid vague anchors like `click here`.
- Do not point every content link to the homepage.

## Review Checklist

Before finalizing SEO internal-linking content:

- [ ] Existing pages were inventoried.
- [ ] Search intent is unique and not duplicated by another page.
- [ ] Page layer is clear: Core / Topic Pillar / Long-tail Support.
- [ ] Content Brief is complete.
- [ ] Parent page exists.
- [ ] At least 2 related pages are identified.
- [ ] Upward, lateral, and conversion links are planned.
- [ ] URL slug is short, readable, and stable.
- [ ] Anchor text is natural and varied.
- [ ] Page is discoverable from a blog index, nav, footer, topic page, sitemap, or equivalent.
- [ ] Content has real unique value beyond keyword coverage.

## Common Mistakes

- Starting with article titles before defining the site structure.
- Publishing long-tail posts without a parent Topic Pillar.
- Creating multiple pages with the same search intent.
- Linking every article only to the homepage.
- Treating SEO content as traffic only, with no conversion path.
- Letting an agent write content before it outputs a Content Brief.

## Agent Rule

When this skill triggers, do not jump straight into writing the article. First output or verify the Content Brief. If the brief cannot identify a parent page, related pages, CTA target, and unique value, stop and ask to reshape the content plan.
