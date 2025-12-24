---
name: ios-open-source-app-study
description: 'A step-by-step Copilot kit (agents/prompts/instructions/docs) to deeply understand an open-source iOS app codebase (Swift/SwiftUI/Xcode), including a foqos case study workflow.'
---

# iOS Open-Source App Study Kit

這個 Skill 提供一套可直接複製到任意 iOS 開源專案的 `.github` 資源：
- Agents：帶你「從入口到模組到 feature」逐步吃透
- Prompts：把“看懂”變成可重複的產出（專案地圖、targets/capabilities、模組拆解、逐檔筆記等）
- Instructions：強制證據驅動、輸出格式一致、避免臆測
- Docs：一份完整的學習教程（含 `awaseem/foqos` 案例走讀）

## 你會得到什麼

- 一條可重複使用的學習流水線：
  1) 快速盤點（入口/targets/依賴/能力）
  2) 模組與資料流（UI/狀態/資料層/副作用）
  3) 逐檔摘要與“建議註釋”（不強制改動原始碼）
  4) 每個功能模塊關鍵知識點清單
  5) 從模塊抽取“如何做類似功能”的實作指南

## 如何使用（拷貝到你的目標倉庫）

1. 把本 Skill 內的模板資料夾整個複製到你的 iOS 專案根目錄：
   - 來源：`skills/ios-open-source-app-study/templates/.github`
   - 目標：`<your-ios-repo>/.github`

2. 在目標倉庫中打開 Copilot Chat：
   - 直接使用 `.github/prompts/` 下的 prompt 逐步產出 `docs/study/` 內容
   - 或啟用 `.github/agents/` 下的 agent 走完整流程

## Bundled Assets

本 Skill 內含資源（請在目標倉庫使用）：
- `templates/.github/agents/`
- `templates/.github/prompts/`
- `templates/.github/instructions/`
- `templates/.github/docs/`

建議先從 `templates/.github/docs/ios-study-workflow.md` 開始。
