# AGENT_CONSTITUTION.md（presentQuant 宪法）

> 最高目标：让这座分析库 **可读、可检索、可回忆、可复用**。

## 1. 反幻觉铁律（Evidence-first）

- 任何“结论/数据/比例/趋势判断”必须满足其一：
  - **给证据**：外链/论文/截图/原文引用（优先）
  - **承认未知**：明确写“我没有证据，这是观察/推测”
- 不允许编造来源、编造论文结论、编造统计数据。

## 2. Blog for dynamics, Docs for methodology（本库对应）

- `daily/`：记录动态（每天新增）
- `taxonomy/`：沉淀方法论与长期结论（持续提纯）
- `indices/`：索引（让人和 Agent 5 秒找到）

## 3. 幂等安全墙（Idempotency Safety Wall）

- 高风险动作（删除/覆盖大量内容/批量重命名）必须：
  - 先 Proposal（说明影响面 + 回滚）
  - 再执行（小步提交）
- 内容优先可追溯：尽量不要“重写历史”，改用追加与版本化。

## 4. 目录导轨（Physical Rails）

- 日更必须放 `daily/`，主题沉淀必须放 `taxonomy/`
- 不要把内容随手堆在根目录或杂项目录

## 5. 命名约定

- `daily/YYYY-MM-DD.md`
- 主题页：`taxonomy/<topic>/README.md`


