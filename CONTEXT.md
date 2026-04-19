# CONTEXT.md — shine-website (Shine Solution Inc 子公司網站)

AI 接續協定: 收到 `resume` → 讀此檔 → 摘要 Current State → 開工。離開前更新並 commit+push。

---

## 🎯 Current State
- **Status**: paused (v2 已發佈)
- **Branch**: `master`
- **Last session**: v2 premium bbtruck-style website with full EN/ZH/KR i18n
- **Working on**: 完成
- **Next step**: 待使用者指示 — 更新公司資訊 / 加第 4 語言 (西班牙文) / 改版
- **Blockers**: 無

## 🗂 Project Overview
- **Purpose**: Shine Solution Inc (BBTruck 子公司) 形象網站
- **Stack**: HTML 純前端 (GitHub Pages 部署)
- **Key paths**: `i18n.json` (完整三語翻譯)
- **Entry points**: https://cph0512.github.io/shine-website/

## 🔑 Key Decisions
- **藍白企業風格** — 相較於 bbtruck.cc 有自己特色
- **EN/ZH/KR 三語** — 已有翻譯完整, 公司實際支援英/中/韓/西四語 (西班牙文待補)
- **GitHub Pages 部署** — 免維運

## 🚧 Pending / TODO
- [ ] 公司資訊更新 (若有)
- [ ] 第 4 語言 (西班牙文)
- [ ] Gemini 額度恢復後出比較版

## 🐛 Known Issues
- Gemini SSH 環境跑不動 (MCP/keychain), 需從 Windows 本機跑

## 📎 External Refs
- GitHub: cph0512/shine-website (public)
- Prod: https://cph0512.github.io/shine-website/
- 參考: bbtruck.cc (母公司)
- 資料: ~/Downloads/美國網站製作Shine solution/

## 公司資訊
- **名稱**: Shine Solution Inc (BBTruck 子公司)
- **營收**: $34M, 40+ 員工
- **倉庫**: Ontario CA (216K sqft) + Chino CA (215K sqft) = 430K+ sqft, 54 dock doors
- **車隊**: 150+ 全美
- **覆蓋**: CA, NJ, NY, AZ, TX, GA, WA
- **服務**: 倉儲/FBA, 海空運, 全美 FTL/LTL, 報關
- **Contact**: ir@bbtruck.cc, steven@shinesolutionusa.com

## 🖥 Environment
- GitHub Pages (自動部署自 master)

## 📜 Session Log
### 2026-04-19 22:30 (m4pro, claude)
- 建立 CONTEXT.md 納入 Resume Protocol (遠端寫入)
- 下次從: 公司資訊更新或第 4 語言

### 2026-03-28 (近期 commits)
- 4fbdb41 v2: premium bbtruck-style + full EN/ZH/KR i18n
- 0a12dca initial bbtruck style EN/ZH/KR
