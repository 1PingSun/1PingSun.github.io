# 1Ping's Blog

這是使用 Hexo 框架建立的個人部落格，主要分享資安、創客、程式設計等相關內容。

## 🚀 自動部署

本專案使用 GitHub Actions 自動部署到 GitHub Pages：

- **分支結構**：
  - `main/master`: 原始碼分支
  - `gh-pages`: 部署分支（自動生成）

- **部署流程**：
  1. 推送程式碼到 `main` 分支
  2. GitHub Actions 自動執行
  3. 建立 Hexo 網站
  4. 部署到 `gh-pages` 分支
  5. GitHub Pages 自動更新網站

## 🛠 本地開發

```bash
# 安裝依賴
npm install

# 清除快取
npm run clean

# 建立網站
npm run build

# 本地預覽
npm run server
```

## 📝 發布新文章

1. 在 `source/_posts/` 目錄下建立新的 Markdown 檔案
2. 設定 front matter（標題、日期、標籤等）
3. 撰寫文章內容
4. 推送到 GitHub，自動部署

## 🎨 主題

使用 [Claudia](https://github.com/Haojen/hexo-theme-Claudia) 主題，並進行了客製化修改。

## 📄 授權

本專案內容採用 MIT 授權條款。
