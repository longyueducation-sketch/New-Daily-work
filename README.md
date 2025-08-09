# Daily Calendar

這是一個可以記錄每日待辦事項與請假學生的互動日曆，支援 Firebase 即時同步。

## 使用方式

1. 登入 GitHub 建立一個新的 Repository，例如 `daily-calendar`。
2. 將 `index.html` 上傳到該 Repository。
3. 登入 [Vercel](https://vercel.com) → 點 "New Project" → 選擇剛剛的 Repository。
4. Framework 選 "Other"，Output directory 留空。
5. 按 "Deploy" 即可獲得專屬網址。

---

## 功能
- Google 登入/登出
- 每位使用者獨立資料（用 Firebase UID 區分）
- 即時同步（多裝置同時更新）
- 每日待辦事項 + 請假學生紀錄
