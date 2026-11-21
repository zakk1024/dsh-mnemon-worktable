# Changelog

## 0.7.0 — 持久工作流（fork: dsh-mnemon-worktable）

- 開工自動 bootstrap：檢查／建立 `<專案資料夾>/AGENT-CONTINUITY.md` 地面真相檔。
- 窗口任務訊息自動注入持久工作流：開工協議、三層記憶與驗證閘門、反幻覺硬規則、收工協議、產物狀態面板要求，並附地面真相檔路徑與狀態。
- 新增公開唯讀端點 `GET /api/worktable/continuity?folder=<abs>`（CORS `*`，只讀 `AGENT-CONTINUITY.md`）：exists、bytes、updatedAt、章節、待驗證數、摘錄。
- HTML 窗口 iframe 網址附帶 `wt_folder` 參數，供產物取得專案資料夾。
- 改名 `dsh-mnemon-worktable`、版本 0.7.0、更新來源改為本 fork；瀏覽器儲存名稱不變，升級不丟專案。
- 知識包更新：本插件以 `lib/*.js` 直接發佈，無 build 步驟。

基於 Aisland-SJL/dsh-worktable 0.6.0（MIT）。
