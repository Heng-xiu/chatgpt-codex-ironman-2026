# ChatGPT Codex 鐵人賽 2026

本專案紀錄 2026 年 iThome 鐵人賽的 30 天系列文章、實作程式碼、操作紀錄與學習筆記，主題聚焦於 ChatGPT Codex、AI Agent 與實際開發工作流。

## 專案介紹

這是一個以「邊參賽、邊實作、邊整理」為核心的公開學習專案。每一天會以獨立的 `DayXX/` 目錄保存文章與素材，讓讀者依照比賽進度閱讀，也能取得範例程式與延伸資料。

本專案的目標是：

- 記錄使用 ChatGPT Codex 解決真實問題的過程。
- 將 AI 輔助開發的方法整理成可重現的步驟。
- 透過每日文章與程式碼，建立可持續累積的實作筆記。

## 給 Agents 的 Prompt

以下 prompt 可以直接複製給 Agents：

```text
你正在協助維護 ChatGPT Codex 鐵人賽 2026 repository。
請遵守根目錄 AGENTS.md：每日內容放在對應的 DayXX/ 目錄，先理解現有結構再修改；
保持繁體中文說明、補充必要的執行方式，不提交 API 金鑰或個人敏感資料，完成後檢查 git diff 與 git status，並清楚摘要修改內容與驗證結果。
```


## 比賽系列連結

- [2026 年，會用 AI 不等於會帶 AI：用 ChatGPT × Codex 從零開始實現一人 AI 團隊 系列](https://ithelp.ithome.com.tw/users/20161074/ironman/9830)

## 每日文章連結

文章發布後，會將當日 iThome 文章連結補充到下表；目前可先從各日目錄查看草稿與實作內容。

| 日期 | 文章標題 | 摘要 |
| --- | --- | --- |
| Day01 | [會用 ChatGPT，不等於會帶 AI：我為什麼開始用 Codex 打造一人 AI 團隊](https://ithelp.ithome.com.tw/articles/10411050) | 建立系列問題與學習地圖 |
| Day02 | [我已經會用 ChatGPT 聊天，為什麼還需要認識 ChatGPT Work 與 Codex？](https://ithelp.ithome.com.tw/articles/10412151) | 如果你已經會使用 ChatGPT，下一步可能不是學更多 Prompt，而是改變你把工作交給 AI 的方式。一般的 ChatGPT 對話，多半停留在「提出問題 → 得到答案」；ChatGPT Work 與 Codex 則進一步讓 AI 接手一個具有明確成果的任務，自己拆解步驟、使用工具、處理檔案、搜尋資料，最後交付可以被人審查的成果。這篇文章將從 ChatGPT Chat、ChatGPT Work 與 Codex 的差異開始，帶你完成 ChatGPT Desktop 與 Work 的基本設定，並進一步理解本地 Work 與雲端 Work 在資料來源、權限與執行環境上的不同。真正重要的改變，不只是 AI 變得更聰明，而是我們開始從「問 AI 問題」，走向「把工作委派給 AI」。 |
| Day03 | 待補 | [Day03](Day03/README.md) |
| Day04 | 待補 | [Day04](Day04/README.md) |
| Day05 | 待補 | [Day05](Day05/README.md) |
| Day06 | 待補 | [Day06](Day06/README.md) |
| Day07 | 待補 | [Day07](Day07/README.md) |
| Day08 | 待補 | [Day08](Day08/README.md) |
| Day09 | 待補 | [Day09](Day09/README.md) |
| Day10 | 待補 | [Day10](Day10/README.md) |
| Day11 | 待補 | [Day11](Day11/README.md) |
| Day12 | 待補 | [Day12](Day12/README.md) |
| Day13 | 待補 | [Day13](Day13/README.md) |
| Day14 | 待補 | [Day14](Day14/README.md) |
| Day15 | 待補 | [Day15](Day15/README.md) |
| Day16 | 待補 | [Day16](Day16/README.md) |
| Day17 | 待補 | [Day17](Day17/README.md) |
| Day18 | 待補 | [Day18](Day18/README.md) |
| Day19 | 待補 | [Day19](Day19/README.md) |
| Day20 | 待補 | [Day20](Day20/README.md) |
| Day21 | 待補 | [Day21](Day21/README.md) |
| Day22 | 待補 | [Day22](Day22/README.md) |
| Day23 | 待補 | [Day23](Day23/README.md) |
| Day24 | 待補 | [Day24](Day24/README.md) |
| Day25 | 待補 | [Day25](Day25/README.md) |
| Day26 | 待補 | [Day26](Day26/README.md) |
| Day27 | 待補 | [Day27](Day27/README.md) |
| Day28 | 待補 | [Day28](Day28/README.md) |
| Day29 | 待補 | [Day29](Day29/README.md) |
| Day30 | 待補 | [Day30](Day30/README.md) |
| Day31 | 待補 | [Day31](Day31/README.md) |

## 使用指南

### 下載專案

```bash
git clone <repository-url>
cd chatgpt-codex-ironman-2026
```

### 瀏覽每日內容

從 [Day01](Day01/README.md) 開始，依序閱讀至 [Day31](Day31/README.md)。每個目錄可放置文章草稿、程式碼、圖片、資料與執行說明。

### 使用範例程式

請先閱讀對應 `DayXX/README.md` 的環境需求與執行方式。若需要環境變數，請參考 `.env.example`，不要把真實金鑰提交到 Git。

## Star 趨勢

如果這個專案對你有幫助，歡迎在 GitHub 點選 Star ⭐，也歡迎提出 Issue 或 Pull Request 分享想法。

[![Star History Chart](https://api.star-history.com/svg?repos=Heng-xiu/chatgpt-codex-ironman-2026&type=Date)](https://star-history.com/#Heng-xiu/chatgpt-codex-ironman-2026&Date)


## 授權

本專案採用 MIT License；詳見 [LICENSE](LICENSE)。

---

如果您覺得這個專案有幫助,請給我們一個星星 ⭐️ 並分享給您的朋友!
