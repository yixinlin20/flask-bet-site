🎲 Flask Betting Simulation Platform

一個使用 Flask 打造的模擬下注遊戲網站，支援 Google 登入、聊天室、商城、排行榜、課金紀錄、每日任務、即時通訊、管理員後台等豐富功能。具備手機版 RWD 支援與現代化 UI 設計，適合展示或作為專案起點。

📦 專案結構

full_project_package/
├── app.py                # 主應用程式
├── templates/            # HTML 模板
├── static/               # CSS / JS / 圖片等靜態資源
├── database/             # SQLite 資料庫檔與初始化腳本
├── .env                  # OAuth 與機密設定檔
├── requirements.txt      # Python 套件需求清單
└── README.md             # 本說明文件

🚀 功能特色

✅ Google OAuth 登入

💬 即時聊天室（分房、舉報、關鍵字過濾）

💡 每日任務與下注歷史

📈 玩家下注統計圖表與排行榜

🛍️ 商城購買虛擬商品

💰 課金紀錄與憑證下載

🔐 管理員後台（可查閱用戶、金流、IP、訊息紀錄）

🛠️ 安裝與執行

1. 安裝相依套件

pip install -r requirements.txt

2. 設定環境變數

請建立 .env 檔案，填入你的 Google OAuth 憑證：

GOOGLE_CLIENT_ID=xxx
GOOGLE_CLIENT_SECRET=xxx
SECRET_KEY=your_flask_secret

3. 啟動伺服器

python app.py

伺服器預設在 http://127.0.0.1:5000 執行。

🌐 部署教學（以 Render 為例）

註冊 Render

建立新 Web Service

上傳專案，選擇主程式為 app.py

在 Render 儀表板新增以下環境變數：

GOOGLE_CLIENT_ID

GOOGLE_CLIENT_SECRET

SECRET_KEY

等待部署完成，即可獲得公開網址

🖼️ 網站預覽圖建議

你可以在 static/preview.png 加上一張網站首頁與聊天室畫面合併圖，方便放在 GitHub README 或社群分享。

我也可以幫你生成這張圖，要的話跟我說一聲 😉

📬 聯絡與貢獻

有任何建議、想法或功能需求，歡迎提出 Issue 或 PR！

