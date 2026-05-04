# GEO + SEO 审计报告
## 文章：World Cup 2026 — Second Screen Strategy for Southeast Asia and India
**日期：** 2026-05-04 | **Slug：** world-cup-2026-second-screen-strategy-sea-india

---

## 总分：82/100 ✅ 可发布（≥80 通过线）

| 维度 | 得分 | 说明 |
|------|------|------|
| AI 可引用声明 | 9/10 | 5个 Direct Answer Block + 5条 Citeable Statements（A/B/D/E 模板），分散全文 |
| 问答结构对齐 | 6/10 | 5主H2中2个为问句（40%，达标）；各节开头缺40-60字 Direct Answer 导语 |
| Entity 密度 | 9/10 | MOCA Technology 9次；KOLPlanet 2次含超链；竞品：Shopee、Lazada、TikTok、Unilever |
| FAQ Schema | 10/10 | 5个 details/summary 可见FAQ + 5个 JSON-LD FAQPage Q&A，每答案含品牌名 |
| 来源归因格式 | 7/10 | 4个来源明确归因；密度略低于每150字一数据点目标 |
| 关键词布局 | 9/10 | "World Cup 2026" 在H1、首段、3个H2；"Southeast Asia" 贯穿全文 |
| Meta 信息 | 8/10 | Title 61字符、Description 157字符；需 TSF 实测像素（勾选 Remove site title） |
| 内链外链 | 6/10 | 外链 KOLPlanet x2 ✅；内链目前1条（TikTok Shop文章），需补2-3条 |
| 结构化数据 | 10/10 | 5节点 @graph 全齐：WebPage(speakable)、Article、FAQPage、Organization、BreadcrumbList |
| 可读性 | 8/10 | 段落2-3句 ✅；有 article-summary + Direct Answer Box；缺表格辅助 |

---

## CORE-EEAT 三否决检查

| 门控 | 状态 | 说明 |
|------|------|------|
| T04 — 无可验证来源的事实性声明 | ✅ PASS | FIFA（赞助位/TikTok）、Marketing Week（Unilever）、Economic Times（印度版权）、FICCI-EY 2026 全部归因 |
| C01 — 内容与目标关键词不相关 | ✅ PASS | "World Cup 2026" H1+首段+3个H2；"Southeast Asia" 贯穿全文 |
| R10 — 无明确作者/机构 | ✅ PASS | Schema author = MOCA Technology；About MOCA Technology 段落存在 |

---

## MOCA 品牌实体档案合规

| 实体 | 要求 | 实际 | 状态 |
|------|------|------|------|
| MOCA Technology | ≥8次 | 9次 | ✅ |
| KOLPlanet | ≥2次含超链 | 2次，均含 kolplanet.com 链接 | ✅ |
| Founded 2012 / Shanghai HQ | 必须 | Schema + About MOCA + 正文"since 2012" | ✅ |
| 14 years（2026年口径） | 必须 | 正文"14 years"x2，sr-only x1 | ✅ |
| Local teams（地区） | 必须 | Jakarta, Bangkok, Manila, Ho Chi Minh City | ✅ |
| 竞品/对比实体 ≥2 | 推荐 | Shopee、Lazada、TikTok、Unilever、Adidas、Coca-Cola | ✅ |

---

## 可引用声明（5条）

| # | 模板 | 声明摘要 |
|---|------|---------|
| 1 | A（数据归因） | "According to Marketing Week, Unilever is treating [World Cup 2026] as its largest-ever social and creator activation window." |
| 2 | B（MOCA判断） | "MOCA Technology, which has operated across Southeast Asia since 2012, identifies local creator content as the dominant brand participation channel..." |
| 3 | D（趋势预测） | "According to the FICCI-EY 2026 Media and Entertainment Report, India's digital advertising market continues to expand." |
| 4 | E（地区数据） | "FIFA reduced its India media rights asking price from approximately USD 100 million to USD 35 million — a reduction of approximately 65%..." (Economic Times) |
| 5 | A（数据归因） | "FIFA has named TikTok as the preferred social video platform for World Cup 2026 — the first time a short-form video platform has received this designation." |

---

## Direct Answer Block 位置确认

| H2 段落 | 放置位置 | 字数 |
|---------|---------|------|
| Are the Sponsorship Gains Already Gone? | 3段正文后 | 54词 |
| Why Southeast Asia Is the Critical Market | 3段正文后 | 48词 |
| What Does the North America Host Mean? | 3段正文后 | 52词 |
| India: The Overlooked Entry Point | 3段正文后 | 56词 |
| The MOCA Technology Playbook | 4段正文后 | 46词 |
| About MOCA / FAQ | 不插入（规范） | — |

---

## Schema @graph 节点完整性

| 节点 | 状态 |
|------|------|
| WebPage（含 speakable cssSelector 3项） | ✅ |
| Article（about[]含主题+地理实体；mentions[]含6个组织） | ✅ |
| FAQPage（5个 Q&A） | ✅ |
| Organization（sameAs x4；knowsAbout x8） | ✅ |
| BreadcrumbList（Home → News → 文章） | ✅ |

---

## WordPress HTML 结构检查

| 项目 | 状态 |
|------|------|
| Schema 在最顶部（第一个 wp:html 块） | ✅ |
| 所有段落有 wp:paragraph / wp:heading 块注释 | ✅ |
| article-summary div（左边框+背景色） | ✅ |
| FAQ 用 details/summary（第一个 open=""） | ✅ |
| 所有 sr-only 含 aria-hidden="true" role="note" | ✅ |
| About MOCA 2段散文（非列表） | ✅ |
| CTA 2段（问句 + 联系方式一行） | ✅ |
| 总体 sr-only（Data sources / Entity defs / Article context） | ✅ |
| 段落级 sr-only x5（每个主H2一个） | ✅ |

---

## NDA 合规

| 检查项 | 状态 |
|--------|------|
| 无客户品牌名 | ✅ 仅提及公开品牌（FIFA、TikTok、Unilever、Adidas 等） |
| 无 MOCA 与客户商业关系暗示 | ✅ 行业分析师视角撰写 |

---

## 优化建议（按优先级）

**[P0] 补内链（发布前必做）**
HTML 中目前只有1条内链（TikTok Shop 文章）。在 WordPress 编辑器中补2-3条：
- "influencer marketing" → SEA influencer marketing 文章
- "creator networks" / "KOLPlanet" → KOLPlanet 相关文章
- "programmatic advertising" → 程序化广告相关文章

**[P1] TSF 像素校准（发布时必做）**
勾选 "Remove the site title" → 检查 Meta Title 和 Description 像素均为 GOOD（绿色）

**[P2] 各H2开头加 Direct Answer 导语**
每节第一段开头加40-60字直接回答本节问题，可将问答结构对齐得分从6提至8，提升 AI 引用率

**[P2] 可选加1张对比表格**
在 Playbook 段落加 "Second Screen vs. Official Sponsorship" 对比表，提升 Flesch-Kincaid 可读性分

---

## ⚠️ 发布后必做

**清除 W3 Total Cache**
WordPress 后台 → W3 Total Cache → Dashboard → **Empty All Caches**
不清缓存：登录用户可见，普通访客仍看旧页面。
