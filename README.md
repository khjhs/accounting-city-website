# 記帳城市官方網站

這是記帳城市 iOS 應用程式的官方網站，包含支援、隱私政策和使用條款等必要頁面，用於 App Store 上架和 AdMob 申請。

## 網站結構

```
website/
├── index.html          # 主頁面
├── support.html        # 使用支援
├── privacy.html        # 隱私政策  
├── terms.html          # 使用條款
├── styles.css          # CSS 樣式文件
└── README.md          # 說明文件
```

## 頁面說明

### 🏠 主頁面 (index.html)
- 應用程式介紹和功能特色
- 響應式設計，支援手機和桌面裝置
- 包含導航連結到其他重要頁面

### 📞 使用支援 (support.html)
- 詳細的常見問題解答 (FAQ)
- 涵蓋應用程式使用、記帳功能、城市建設、資料管理等主題
- 技術支援和故障排除指南
- 聯繫資訊

### 🔒 隱私政策 (privacy.html)
- 符合 App Store 和 AdMob 要求的隱私政策
- 詳細說明資料收集、使用和保護措施
- 包含 AdMob 廣告服務相關資訊
- 兒童隱私保護說明

### 📋 使用條款 (terms.html)
- 完整的使用條款和服務協議
- 涵蓋使用許可、用戶責任、免責聲明等
- 虛擬貨幣（遊戲幣）使用規範
- 知識產權保護條款

## AdMob 廣告資訊

本網站已包含以下 AdMob 廣告單元的相關資訊：

- **橫幅廣告**: `ca-app-pub-8840276860116384/1036537387`
- **獎勵廣告**: `ca-app-pub-8840276860116384/2808784052`

## 部署到 GitHub Pages

### 步驟 1: 創建 GitHub 倉庫
1. 在 GitHub 上創建新的公開倉庫
2. 倉庫名稱建議：`accounting-city-website`

### 步驟 2: 上傳檔案
```bash
# 初始化 git 倉庫
cd website
git init

# 添加所有檔案
git add .
git commit -m "Initial website setup for Accounting City"

# 連接到 GitHub 倉庫（替換為您的倉庫地址）
git remote add origin https://github.com/YOUR_USERNAME/accounting-city-website.git
git branch -M main
git push -u origin main
```

### 步驟 3: 啟用 GitHub Pages
1. 進入倉庫的 Settings 頁面
2. 滾動到 "Pages" 設定
3. 在 "Source" 中選擇 "Deploy from a branch"
4. 選擇 "main" 分支和 "/ (root)" 目錄
5. 點擊 "Save"

### 步驟 4: 獲取網站地址
完成設定後，您的網站將在以下地址可用：
```
https://YOUR_USERNAME.github.io/accounting-city-website/
```

## 重要網址

部署後，以下是您需要在各種申請中使用的重要網址：

- **主網站**: `https://YOUR_USERNAME.github.io/accounting-city-website/`
- **隱私政策**: `https://YOUR_USERNAME.github.io/accounting-city-website/privacy.html`
- **使用條款**: `https://YOUR_USERNAME.github.io/accounting-city-website/terms.html`
- **支援頁面**: `https://YOUR_USERNAME.github.io/accounting-city-website/support.html`

## App Store 申請使用

在 App Store Connect 中填寫應用程式資訊時，請使用：

- **App 網站**: 主網站地址
- **隱私政策 URL**: 隱私政策頁面地址
- **支援 URL**: 支援頁面地址

## AdMob 申請使用

在 AdMob 申請過程中，如需提供網站資訊，請使用：

- **網站 URL**: 主網站地址
- **應用程式描述**: 可參考主頁面的內容
- **隱私政策**: 隱私政策頁面地址

## 維護說明

### 更新網站內容
1. 直接在 GitHub 上編輯檔案，或
2. 本地修改後推送到倉庫：
```bash
git add .
git commit -m "Update website content"
git push
```

### 自定義域名（可選）
如果您有自己的域名，可以在倉庫中添加 `CNAME` 檔案：
```bash
echo "your-domain.com" > CNAME
git add CNAME
git commit -m "Add custom domain"
git push
```

## 技術特性

- ✅ 響應式設計，支援手機和桌面
- ✅ 現代化的 CSS Grid 和 Flexbox 佈局
- ✅ 符合無障礙設計原則
- ✅ SEO 友善的 HTML 結構
- ✅ 快速載入和優化效能
- ✅ 支援多種螢幕尺寸

## 支援

如有網站相關問題，請聯繫：
- 電子郵件：support@accountingcity.com

---

© 2024 記帳城市. 版權所有.