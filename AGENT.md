# AGENT.md（给 Cursor / Claude Code / Kiro 等编码代理）

> 最高准则：开始任何工作前，先读 `AGENT_CONSTITUTION.md`。

## 1. 这个仓库是什么？

`presentQuant` 是一个**日更研究分析库**：把研究材料（论文/博客/推文/报告/代码）沉淀为结构化笔记与方法论，方便人和 Agent 阅读、思考、使用与回忆。

## 2. 内容写到哪里？

- **动态（日更）**：`daily/`
  - 命名：`YYYY-MM-DD.md`
  - 目标：记录当天最重要的 1-3 条研究输入，并输出你的结论与行动项
- **方法论（主题沉淀）**：`taxonomy/`
  - 每个一级主题一个目录，主题首页写在 `README.md`
- **索引（检索入口）**：`indices/`
  - `topics.md`：按主题
  - `timeline.md`：按日期
  - `glossary.md`：术语口径

## 3. 写作协议（强约束）

- **先结论，后展开**：每篇至少给 3 点结论
- **证据优先**：没有证据就标注“观察/推测”
- **可执行清单**：每篇落 3-7 条行动项

## 4. 模板（强烈建议用）

- 日更：`templates/research-note.md`
- 论文解构：`templates/paper-xray.md`
- 本质卡片：`templates/essence-card.md`
- 决策记录：`templates/decision-record.md`

## 5. 提交规范（如果由 Agent 提交）

- 小步提交，commit message 推荐：
  - `feat: add daily note YYYY-MM-DD`
  - `docs: update taxonomy <topic>`
  - `docs: update indices`


