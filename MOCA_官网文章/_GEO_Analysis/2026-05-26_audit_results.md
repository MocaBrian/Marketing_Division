# Otterly.AI GEO Audit Results — MOCA 官网文章

**审计日期**: 2026-05-26
**工具**: Otterly.AI Content Checker (GEO Audit Tools)
**审计范围**: 2025-05-08 → 2026-05-20 共 14 篇 moca-tech.net/news 文章
**配额消耗**: 14/100 月配额

---

## 📊 完整评分表

| # | Date | Article Slug | Static | Readiness | Structured |
|---|---|---|---|---|---|
| 1 | 2026-05-20 | tiktok-search-first-shift-sea-2026 | 99 | 75 | 77 |
| 2 | 2026-05-05 | world-cup-2026-second-screen-strategy-sea-india | 99 | **77** | 77 |
| 3 | 2026-05-05 | oil-price-crisis-southeast-asia-content-commerce-growth | 99 | 69 | 79 |
| 4 | 2026-05-05 | tiktok-shop-rule-change-search-first-content-sea-2026 | 99 | 72 | 76 |
| 5 | 2026-05-05 | tiktok-shop-indonesia-ban-to-13-billion-gmv-comeback | 99 | **78** | **84** |
| 6 | 2026-02-06 | moca-annual-gala-celebration-talent-in-every-sense | 99 | 63 | 83 |
| 7 | 2025-12-31 | welcoming-2026-moca-technology-thanks-our-partners | 98 | 66 | **85** |
| 8 | 2025-12-19 | global-social-media-under-16-ban-2025 | 99 | 67 | **85** |
| 9 | 2025-10-24 | ai-content-regulations-tighten | 98 | 62 | 80 |
| 10 | 2025-09-12 | seize-indias-gst-breakthrough | 99 | **55** ⚠️ | 84 |
| 11 | 2025-08-29 | tiktoks-new-compliance-wave | 99 | 67 | 77 |
| 12 | 2025-08-21 | platform-policy-tightening-2025 | 99 | 69 | 79 |
| 13 | 2025-08-06 | moca-shines-at-chinajoy-2025 | 98 | **58** ⚠️ | 80 |
| 14 | 2025-05-08 | how-to-drive-real-growth-in-indonesia | 97 | 63 | 76 |
| | **AVG** | | **98.5** | **67.2** | **79.9** |

---

## 🎯 三维评分洞察

### 1. Static vs Dynamic — 平均 98.5%（已达标）
全部 14 篇都在 97-99%。Wix SSR 让所有内容对 LLM Crawlers (GPTBot/ClaudeBot/PerplexityBot) 都是静态可读的。技术层 GEO 基础已 OK，不是瓶颈。

### 2. Readiness Analysis — 平均 67.2%（**主战场**）
- 范围 55-78，方差最大
- **Top 3**: tiktok-shop-indonesia-ban (78) / world-cup-2026 (77) / tiktok-search-first-shift (75)
- **Bottom 3**: seize-indias-gst (55) / moca-shines-at-chinajoy (58) / moca-annual-gala (63) / how-to-drive-real-growth-in-indonesia (63)

### 3. Structured Data Analysis — 平均 79.9%（schema 加分明显）
- 范围 76-85
- **Top**: welcoming-2026 (85) / under-16-ban (85) / indonesia-ban (84) / india-gst (84)
- **Bottom**: tiktok-shop-rule (76) / indonesia-growth (76) / tiktok-search-first (77)
- ⚠️ 注意：tiktok-search-first 加了 5 节点 @graph + articleSection + reviewedBy 仍 77 → schema 不是 readiness 短板的解药

---

## 🔍 Readiness 子维度（从 tiktok-search-first 详细报告）

| 子维度 | 分数 | 解读 |
|---|---|---|
| Acronyms and Terminology | 85 | AHR / PP Tunas / KOLPlanet 缩写定义清晰 |
| Illustration Opportunities | 85 | 可加图表机会被识别 |
| Readability | 80 | 句长可读 |
| Paragraph Cohesion | 80 | 段落衔接 |
| Tone and Language Check | 80 | 商业语调一致 |
| External Link Suggestions | 75 | 5 个外链够但可更多 |
| Clarity and Assertiveness | 75 | 论点清晰 |
| Modular Content Enhancements | 70 | 段落模块化可改进 |
| Jargon and Metaphors | 70 | 行业术语略多 |
| **Specificity** | **65** | **最低 — 数据点 / 案例细节不够具体** |

---

## 📈 时间趋势

- **2025-05 → 2025-10 旧文**：Readiness 55-67%（无 moca-official-post skill，平均 64%）
- **2026-05 新文（skill 时代）**：Readiness 69-78%（平均 74%）
- **提升幅度**：+10 个百分点

**moca-official-post skill 已经把 Readiness 从平均 64 推到 74，新天花板要靠提升 Specificity 子项**

---

## 🎯 5 类内容 × GEO 表现矩阵

| 内容类型 | 样本 | 平均 Readiness | 平均 Structured | 备注 |
|---|---|---|---|---|
| Long-form data 分析 | #1 #2 #3 #4 #5 #8 #11 #12 | **72** | **80** | 主力，readiness 高 |
| Brand event | #6 #7 #13 | **62** | **83** | Schema OK 但 readiness 低 |
| Policy 解读 | #9 #10 | **59** | **82** | 抽象论点多，最差 readiness |
| Region 增长策略 | #14 | **63** | **76** | 早期文章，schema 弱 |

---

## 💡 关键优化机会（按优先级）

### P0 - 立即可做
1. **Specificity 是最大杠杆**（最低分 65%）
   - 每个论点配具体数据点（X% / Y million / 来源 + 日期）
   - 避免 "many brands" / "significant impact" 类模糊词
2. **Brand event 文章模板需重做** — readiness 比 long-form 低 10 分
   - 加 3-5 个数据点（参会人数 / 合作品牌数 / 出席嘉宾级别）
   - 加 1 段"行业 take" 而非纯叙事

### P1 - 中期改进
3. **Modular Content** (70%) — 多 H3 分段、加 bullet list、加 TL;DR box
4. **External Links** (75%) — 每篇 ≥ 5 个外链到权威源 deep link，不只主页根目录
5. **Jargon and Metaphors** (70%) — 第一次出现术语紧跟一句解释

### P2 - 长期持续
6. **Structured Data 78 → 85+** — 把 #7/#8 的 schema 模式（85 分）抽出来反向应用
7. **Content Checker 每月跑新文** — 月配额 100 够用

---

## 🛠️ Otterly.ai 工具操作要点（写 skill 用）

- **登录态**: Brian 在 Tabbit Chrome 已登录 OtterlyAI（trial 14 天）
- **Workspace**: "Your First Workspace" → Brand Report "Moca-tech"
- **Audit 工具**: 左侧 GEO Audit Tools → Content Checker
- **配额**: 100 GEO URL Audits/月（每篇 1 次）
- **反爬机制**: ⚠️ JS click 被忽略，必须真鼠标点 Start Audit 按钮（坐标约 1347, 332）
  - JS 填 URL 可以
  - Start audit 必须 `computer:left_click`
- **单次 audit 时长**: 30-90s
- **3 大评分维度**: Static vs Dynamic / Readiness Analysis / Structured Data Analysis
- **结果页**: `/geo-audit/content/<audit_id>` — 可 Download Report PDF
- **失败模式**: 提交后 30s 还在 skeleton → 刷新页面

---

## 📂 Audit History

所有 14 个 audit ID 在 https://app.otterly.ai/geo-audit/content 列表中可直接点击查看完整报告。
