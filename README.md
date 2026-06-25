# 胖丁日記 Pang Ding Website

這是一個以英國短毛貓「胖丁」為主角的單頁網站。  
網站以溫暖柔和的色系、圓角卡片、照片排版與互動功能，呈現胖丁的日常紀錄。

## 專案介紹

本專案使用 HTML、CSS、JavaScript 製作，主要程式碼集中在 `index.html`。  
網站內容包含胖丁介紹、日常照片、成長紀錄、年齡換算器，以及可儲存在瀏覽器中的體重紀錄功能。

這個專案的目標是練習從需求出發，透過 Codex 逐步完成一個有設計感、可互動、可放上 GitHub 展示的靜態網站。

## 使用技術

- HTML5
- CSS3
- JavaScript
- CSS Grid
- Flexbox
- Responsive Web Design
- localStorage
- SVG 趨勢圖
- dialog 彈窗
- IntersectionObserver
- Google Fonts

## 已完成功能

- Hero 首頁區
- 胖丁基本介紹
- 日常照片展示
- 成長紀錄
- 聯絡區與 Instagram 連結
- 年齡自動計算
- 貓咪年齡換算器
- 手機版響應式設計
- 滑鼠懸停動畫
- 滾動淡入動畫

### 體重紀錄功能

- 新增日期與體重
- 使用 localStorage 儲存資料
- 顯示最近 5 筆紀錄
- 顯示最新體重
- 顯示最高體重
- 顯示最低體重
- 顯示平均體重
- 顯示總紀錄數
- 重複日期時可選擇是否覆蓋
- 最近 10 筆體重趨勢圖
- 刪除單筆體重紀錄
- 刪除前顯示確認訊息
- 匯出 CSV 資料

## 我在這個專案中練習到的 Codex 實戰流程

- 將網站需求拆成可執行的開發步驟
- 從零建立單頁靜態網站
- 依照指定風格調整 UI 與版面
- 將遠端圖片替換成本地真實照片
- 根據瀏覽器畫面回饋修正手機版問題
- 逐步新增 JavaScript 互動功能
- 先分析問題，再進行程式修改
- 保留既有設計，只針對指定功能調整
- 使用 localStorage 管理前端資料
- 製作資料統計、趨勢圖、CSV 匯出與刪除流程
- 整理 README，讓專案更適合放到 GitHub

## 如何開啟專案

### 方法一：直接開啟檔案

1. 下載或複製本專案
2. 打開 `index.html`
3. 使用瀏覽器查看網站

### 方法二：使用本機伺服器

在專案資料夾中執行：

```bash
python -m http.server 8000
```

接著在瀏覽器開啟：

```text
http://localhost:8000
```

如果要用手機查看，請讓手機與電腦連到同一個 Wi-Fi，並使用電腦的區域網路 IP 開啟。

## 未來可新增功能

- 體重資料匯入功能
- 體重紀錄備註欄位
- 照片燈箱瀏覽模式
- Gallery 手機版照片說明優化
- SEO 與社群分享預覽設定
- Favicon
- 圖片 WebP 優化
- 將 CSS 與 JavaScript 拆成獨立檔案
- 部署到 GitHub Pages、Netlify 或 Vercel
