# 2026_agent_literature-gap — 我的班級工具總專案

## 對話開始時請先讀
進度與最近更動都在 Obsidian：`G:\我的雲端硬碟\Obsidian\literature-gap\工作筆記.md`

## 工作模式
- **加新工具**：對 Claude 說「我想做一個 XXX 工具」→ Claude 會建 `tools/<工具名>/` 子資料夾、引導跟著影片做
- **結束工作**：對 Claude 說「**收工**」→ 自動 commit + push + 更新 Obsidian 工作筆記
- **接續工作**：對 Claude 說「讀工作筆記、告訴我上次做到哪」

## 工作桌 + 三個家
- 📋 GDrive 工作桌：`G:\我的雲端硬碟\Claude_AI_Agents\2026_agent_literature-gap\`（工具 code）
- 📂 GDrive 研究資料：`G:\我的雲端硬碟\Claude_AI_Agents\100_Research\`（素材 / 報告 / 數據，跨電腦同步）
  - `reference/papers/`：論文 PDF 素材
  - `notes/ideas/`：缺口分析報告輸出
  - `data/`：實驗數據參照
- 🐙 GitHub repo：`yuanc669/2026_agent_literature-gap`（公開，網頁的家）
- 📘 Obsidian 駕駛艙：`G:\我的雲端硬碟\Obsidian\literature-gap\工作筆記.md`（想法的家）
  - Obsidian 同步鏡像：`Obsidian/literature-gap/100_Research/notes/ideas/`

## 工具清單
（之後加新工具時會自動更新）
- **literature-gap**：文獻研究缺口分析（三軸缺口 + 集群對接 + 計畫書英文段落）→ `/literature-gap`
  - 素材來源：`Claude_AI_Agents/100_Research/reference/papers/`
  - 報告輸出（雙存）：`Claude_AI_Agents/100_Research/notes/ideas/` + Obsidian 鏡像

## 工作注意事項
- 學生資料一律去識別化（只用座號 + 班級代號）
- commit 訊息要寫清楚做了什麼 + 為什麼
- 收工前說「收工」讓 Claude 同步三方
