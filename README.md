# 霓虹戰姬 (Neon Valkyrie)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)
![Status](https://img.shields.io/badge/status-Completed-success)

《霓虹戰姬》是一款結合賽博朋克風格與時間循環機制的網頁解謎遊戲。玩家將扮演身處霓虹都市中的戰姬，利用時間重複與迴圈的特質，打破因果連鎖，破解重重關卡與謎題。

---

## 🎮 遊戲玩法 (Game Dynamics)

* **核心機制：時間循環 (Time Loop)**
  * 玩家在限定時間內進行探索與操作，時間結束或觸發失敗條件時，會自動回到時間點陣（Reset）。
  * 雖然位置與場景會重置，但玩家獲得的**關鍵情報、密碼與記憶碎片**將會保留。
* **解謎要素 (Puzzle Solving)**
  * 利用前幾次循環獲得的資訊，提前避免危險或解開原本無法開啟的機關。
  * 結合邏輯推理解謎、環境互動以及序列密碼解鎖。

---

## 🤖 使用的 AI 提示詞 (AI Prompts Used)

本專案在開發過程中，利用 AI 輔助進行程式碼架構設計、關卡解謎邏輯與視覺風格生成。以下為主要使用的提示詞範例：

### 1. 遊戲邏輯與時間機制 (Game Logic & Time Loop)
> "請幫我用 JavaScript 實作一個『時間循環 (Time Loop)』機制。當倒數計時歸零時，重置玩家的位置與關卡狀態，但保留 `playerInventory` 與已解鎖的知識標籤（`knowledgeFlags`）。請提供乾淨且模組化的程式碼。"

### 2. 賽博朋克視覺風格與 UI (Cyberpunk UI & Visuals)
> "請使用 HTML5 Canvas 與 Tailwind CSS 設計一個賽博朋克 (Cyberpunk) 霓虹風格的遊戲介面。需要包含脈衝霓虹燈光效果、掃描線 (Scanlines) 濾鏡，以及具備科技感的 HUD 介面（包含倒數計時器與任務目標提示）。"

### 3. 解謎關卡設計 (Puzzle Design)
> "請設計一個需要利用『跨時間循環』才能解開的謎題機制。例如：在第一個循環中看到密碼，但在第一個循環無法輸入；必須等待重置後，利用記憶直接在第二個循環輸入密碼以開啟隱藏通道。"

---

## ✅ 已完成的功能 (Features)

- [x] **時間循環系統**：計時器機制、場景自動重置、跨循環狀態（State Persistence）保存。
- [x] **動態解謎互動**：物品收集、環境機關觸發、密碼鎖定與解鎖系統。
- [x] **賽博朋克視覺 UI**：霓虹光暈特效、賽博風格字體與動態 HUD 顯示。
- [x] **音效與視覺回饋**：按鈕互動、時間重置動畫與關卡完成提示。
- [x] **響應式網頁設計 (RWD)**：支援桌上型電腦與行動裝置瀏覽器遊玩。

---

## 🕹️ 操作方式 (Controls)

| 操作 / 按鍵 | 功能說明 |
| :--- | :--- |
| **W / A / S / D** 或 **方向鍵** | 控制角色移動 |
| **Space (空白鍵) / E** | 與環境物件、機關或 NPC 進行互動/調查 |
| **R** | 手動重置當前時間循環（重新開始） |
| **Esc** | 開啟 / 關閉 遊戲選單與狀態欄 |
| **滑鼠左鍵** | UI 介面點擊與謎題介面操作 |

---

## 🔗 作品連結 (Play Now)

可以直接點擊下方連結或開啟本地檔案進行遊玩：

👉 **[立即遊玩《霓虹戰姬》] 👉 https://share.gemini.google/juar8WqfEwy5

---

## 🛠️ 開發技術 (Tech Stack)

* **前端架構**：HTML5, CSS3, JavaScript (ES6+)
* **樣式與特效**：Tailwind CSS / Canvas API
* **版本控制**：Git & GitHub

---

## 📄 授權條款 (License)

本專案採用 [MIT License](LICENSE) 授權。
