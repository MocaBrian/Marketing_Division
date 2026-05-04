# MOCA 官网文章 Skill 建设计划

**创建日期：** 2026-03-27
**状态：** 待执行
**优先级：** P1

---

## 目标

建立 `moca-official-post` skill，完整覆盖 moca-tech.net 官网 News 文章的撰写、SEO/GEO 优化、品牌审核和发布流程。

## 待完成步骤

### Phase 1: 收集官网写作风格知识库

1. **读取 2025/05 后所有官网文章**（至少10篇），分析：
   - 标题格式（冒号分隔、长度、hook类型）
   - 文章结构（H2数量、段落长度、数据密度）
   - CTA格式（About MOCA boilerplate、contact信息）
   - 语调（professional thought leadership）
   - 数据引用格式
   - 内链/外链策略

2. **分析最新一篇的 GEO 优化方式**
   - H2 是否用问句格式
   - 是否有 FAQ section
   - Schema markup 类型
   - Entity 密度和 MOCA 提及次数

3. **保存分析结果到知识库**
   - 路径：`/Users/brian/Documents/Marketing_Division/知识库/moca_official_post_styleguide.md`

### Phase 2: 组建 Agent Team 做深入研究

| 角色 | Agent | 职责 |
|------|-------|------|
| 行销总监 | Marketing Division | 统筹协调 |
| SEO/GEO优化师 | SEO Specialist + geo-seo-auditor skill | 搜索优化规范 |
| 产品经理 | Sprint Prioritizer | 功能设计和流程审核 |
| 研发工程师 | Frontend Developer | 技术实现（schema、HTML结构） |
| 品牌审核师 | Brand Guardian + moca-brand-enforcer skill | 品牌一致性 |
| CEO | plan-ceo-review skill | 最终策略审核 |

### Phase 3: 创建 moca-official-post Skill

Skill 路径：`~/.claude/skills/moca-official-post/SKILL.md`

核心流程：
```
1. 输入：公众号中文文章（已通过审核的终稿）
2. 风格分析：自动匹配官网写作规范
3. 内容转写：中文→英文，调整视角和深度
4. GEO 优化：问句H2、FAQ section、entity密度、definitive statements
5. SEO 优化：meta信息、关键词布局、内链策略
6. Schema 标记：Article + FAQPage + BreadcrumbList JSON-LD
7. 品牌审核：About MOCA boilerplate、KOLPlanet交叉引用
8. 输出：完整 HTML + meta信息 + schema代码
```

### Phase 4: 相关 Skill 查找

用 `npx skills find` 搜索：
- website content writing
- technical SEO
- schema markup
- GEO optimization
- content repurposing

看是否有可以安装整合的现有 skill。

## 依赖的现有资源

- 官网文章10篇已在之前 session 用 WebFetch 读过（部分摘要保存在 context 中）
- `geo-seo-auditor` skill 已创建
- `article-repurposer` skill 已创建
- `moca-brand-enforcer` skill 已创建
- 品牌色卡和Logo在 `/Users/brian/Downloads/元素/MOCA/`
- 写作风格指南在 `/Users/brian/Desktop/微信公众号_知识库/MOCA公眾號/MOCA_公众号写作风格指南.md`

## Chrome 调试端口注意事项

Chrome DevTools MCP 需要 Chrome 用 `--remote-debugging-port=9222` 启动。当前 PID 73199 已在 9222 端口监听，但 MCP 连接有问题。下次 session 可以试：
```bash
# 先关掉所有 Chrome
pkill -f "Google Chrome"
# 重新用调试模式启动
/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --remote-debugging-port=9222 &
```

---

*下次 session 跟我说"继续官网文章 skill 计划"即可。*
