# 🎸 五月天 阿信相片館 | Mayday Ashin Gallery

一個輕量、響應式且具備 IG 風格的五月天阿信主題相片收藏館。支援圖片自動壓縮儲存、分類標籤管理、檢視/編輯模式切換，以及 Firebase 雲端資料庫實時同步。

> 網頁：https://kaichen0621.github.io/ashin/


![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)

---

## ✨ 核心特色

- **📸 快捷貼上與自動壓縮**：支援直接使用鍵盤快捷鍵 (`Cmd + V` / `Ctrl + V`) 貼上剪貼簿圖片，並透過 Canvas 自動將檔案壓縮 90% 以上，避免塞爆瀏覽器 LocalStorage 容量。
- **🌓 深淺色主題切換**：內建深色（Dark）與淺色（Light）視覺模式，自動記憶使用者的主題偏好。
- **✏️ 雙重模式（檢視 / 編輯）**：可一鍵切換「檢視模式」與「編輯模式」，防止日常瀏覽時誤觸刪除或編輯按鈕。
- **🏷️ 自訂標籤管理**：可自由新增、重新命名或刪除相片分類標籤，並支援依標籤即時篩選與關鍵字搜尋。
- **☁️ Firebase 雲端同步**：整合 Firebase Realtime Database，自動儲存並同步跨裝置的相片資料與下載數據。
- **📱 響應式設計 (RWD)**：專為行動裝置優化的底部導覽列與彈性網格排版，在手機與電腦端皆能完美呈現。

---

## 🛠️ 技術棧

- **前端**：HTML5, CSS3 (原生變數 & Grid/Flexbox), ES6+ JavaScript
- **字型**：Google Fonts (`Plus Jakarta Sans`, `Noto Sans TC`)
- **雲端資料庫**：Firebase Realtime Database (Web SDK v10)
- **本地儲存**：LocalStorage + HTML5 Canvas API (用於圖像 resize 壓縮)

---

## 📂 專案結構

```text
.
├── index.html       # 主程式碼 (包含 UI、樣式與 JavaScript 邏輯)
├── ashin.jpg        # 大頭貼預設圖片 (或 ashin.png)
└── README.md        # 專案說明文件