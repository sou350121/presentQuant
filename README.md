# presentQuant：日更研究分析库（给人和 Agent 的可回忆知识库）

> 目标：把每天的研究/阅读/观察沉淀成 **可检索、可复用、可复盘** 的“分析库”。
> 
> 形态：GitHub 直读（纯 Markdown），结构参考 handbook 风格（如你提到的 VLA-Handbook）。

---

## 1️⃣ 你可以怎么用（3 分钟上手）

1️⃣ **每天新增一条研究笔记**：放到 `daily/YYYY-MM-DD.md`  
2️⃣ **把结论提纯到主题**：放到 `taxonomy/<topic>/README.md`  
3️⃣ **维护索引入口**：更新 `indices/topics.md` 与 `indices/timeline.md`

> 如果你懒得写结构：直接复制 `templates/research-note.md` 开始填空。

---

## 2️⃣ 目录（推荐从这里开始）

- **按主题浏览（主入口）**：`indices/topics.md`
- **按时间回忆（时间线）**：`indices/timeline.md`
- **术语表（统一口径）**：`indices/glossary.md`

---

## 3️⃣ 写作规范（给自己 & 给 Agent）

- **结论先行**：先给 3 点结论，再展开机制与证据
- **证据优先**：关键判断必须附链接/截图/数据；无证据则标注“观察/推测”
- **可执行清单**：每篇笔记尽量落 3-7 条行动项（否则知识无法复用）

更多规则见：
- `AGENT_CONSTITUTION.md`
- `AGENT.md`

---

## 4️⃣ 结构说明（Physical Rails）

```text
presentQuant/
  README.md
  AGENT.md
  AGENT_CONSTITUTION.md
  CONTRIBUTING.md
  LICENSE

  taxonomy/            # 主题树（长期沉淀）
  daily/               # 日更（动态记录）
  indices/             # 索引入口（可检索）
  templates/           # 模板（可复用）
  attachments/img/     # 图片/截图
  runbooks/            # 维护手册
```


