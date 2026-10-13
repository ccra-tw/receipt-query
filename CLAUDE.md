# 物資收據整合查詢（receipt-query）

CCRA 資訊部開發案。需求來源：2026-10-13 資訊部會議——捐贈者來電查收據時，物資、食物、7-11、好康抱抱等各類收據分散，要一個整合查詢。
業務單位提供原始資料（Excel 總檔）、收據樣本與希望的查詢方式後開始（約 11 月）。
**本 repo 公開，Issues 全世界看得到**（熊哥 2026-10-14：「公開 issues 可以避開內部資訊，搭配 Planner 處理」）。
Issue 只寫功能、需求與技術決定；**不寫**：主機 IP、內部網段、帳號密碼與金鑰、同工或捐贈者姓名與個資、真實收據資料。
這些細節放 CCRA Planner「資訊部共同事務」對應的票，Issue 內只寫「細節見 Planner 票 <前 8 碼>」。

## Agent skills

### Issue tracker

Issues live in this repo's GitHub Issues (ccra-tw/receipt-query), via the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels

Default five-role vocabulary (needs-triage, needs-info, ready-for-agent, ready-for-human, wontfix). See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: `GLOSSARY.md` + `docs/adr/` at the repo root, created lazily. See `docs/agents/domain.md`.
