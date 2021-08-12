# 作品列表
以下介紹在學習前端的過程中所撰寫的專案作品，並列出一些技術成就：

1. [品牌形象網站](https://cloudyclee.github.io/Brand_website/dist/index.html)
	- 使用 SASS 撰寫 css 檔 (後續專案均如此)
	- 使用 Bootstarp 元件與格線系統規劃版面與排版
	- 使用 jQuery 撰寫網頁互動效果
		
		* 區塊式滾動
		* 導覽列隨背景變色
		* 回到頂部按鈕
		* 點擊導覽列自動滾動至對應區塊
		
	- 使用 skrollr 及 AOS 套件設計網頁動畫

2. [訂房網站前端頁面](https://cloudyclee.github.io/Hotel-reservation/)
	- 根據設計稿進行切版
	- 自行設計 RWD 版型
	- 使用 Ajax 向 API get 房型資料與訂房日期；post 訂房資料
	- 以網址帶參數形式實作單頁式網站
	- 使用 vue 的模板語法實現網頁互動
	- 自行撰寫日曆元件
	- 驗證使用者填寫資訊
	- 根據 API 回傳結果給予使用者回饋畫面

3. [新接龍](https://cloudyclee.github.io/Free_cell/)
	- 使用 vue composition API 進行撰寫，以操作資料為原則更新 DOM
	- 自行撰寫拖曳事件 (非使用原生或 jQuery 的拖曳事件)
	- 可重開新局、重新開始、復原
	- 若符合規則，可自動歸牌
	- 提示可移動的牌組
	- 可計時計步，並且復原或自動歸牌都不計步數
	- 自行設計洗牌動畫
	- 自動判定輸贏，並根據判定結果給予使用者回饋

4. [記帳程式](https://cloudyclee.github.io/MyWallet/)
######伺服器若30分鐘未有請求則會暫停，因此第一次連線需等伺服器重啟
	- 自行開設 API 並部署在 Heroku 上供前端串接
	- 使用 passport.js 與 jwt 套件實作 JSON web token 登入系統
	- 加入mongoose model 以驗證、存取、更新、刪除資料
	- 使用 joi 套件驗證前端傳回來的資料
	- 使用 Vue CLI 部署開發環境
	- 使用 Element plus 製作簡易的介面，並設定響應式行為
	- 實作前端 Google 一鍵登入按鈕
	- 使用模組化的 Vuex 和 local Storage 管理使用者資料和憑證
	- 以 Vue Router 配置嵌套路由和動態路由
	- 設定路由守衛限制訪客查看需登入的頁面
	- 實作 Axios 攔截器處理等待時間與統一錯誤處理
	- 以模組化的方式統一 API 進入點
	- 使用 echarts 套件繪製分析圖表
  
  
