# Agent 總管理 Skill

## 用途
追蹤當前活躍的專案上下文，確保並行工作時不會混淆。

## 活躍專案
（每次執行任務前需確認並更新此處）

| 專案名稱 | 工作目錄 | 專案 Skill |
|---------|---------|-----------|
| agent（主） | `/Users/jackchou/Desktop/agent` | - |
| stock-investor | `/Users/jackchou/Desktop/agent/projects/stock-investor` | `.opencode/SKILL.md` |

## 工作模式

### 切換專案上下文
當用戶提到某個專案時，更新「活躍專案」狀態：
```
[活躍專案]: stock-investor
```

### 執行任務前
1. 確認當前任務屬於哪個專案
2. 如有需要，載入該專案的 skill
3. 閱讀該專案的 `MEMORY.md`

### 多專案並行
- 為每個專案啟動獨立的工作階段
- 或明確標記專案名稱避免混淆

## 專案建立清單
新專案建立時需完成：
- [ ] 在 `projects/` 建立資料夾
- [ ] 建立 `MEMORY.md`
- [ ] 建立 `.opencode/SKILL.md`
- [ ] 在 GitHub 建立獨立 Repo
- [ ] 更新上方「活躍專案」表格
- [ ] 更新 agent/MEMORY.md 的「子專案清單」

## 重要約定
- **語言**: 所有回覆與 Markdown 文件皆使用繁體中文
- **所有 Markdown 文件**: 皆需使用繁體中文，嚴禁簡體中文

## 當前任務記錄
（每次對話開始時重置）
- 無
