# 最新上映院線電影訂閱通知網站

[![hackmd-github-sync-badge](https://hackmd.io/utQQsBerRj-ss5TVq3jWaA/badge)](https://hackmd.io/utQQsBerRj-ss5TVq3jWaA)

會想做這個網站是因為我很愛看電影，但是每次想要知道最近有什麼新電影上映都要開電影院的網站或是 App 查看，覺得很麻煩，所以就興起了一個念頭，那不如就來做個網站吧!根據類型將電影分類，我可以根據我喜歡的電影類型訂閱電影上映通知，一旦有該類型電影要上映或即將上映，就會寄簡訊或電子郵件通知我，我就可以知道有什麼超棒的電影上映了!
## 使用者故事
### 前端
1. 身為一個電影愛好者，我希望主頁可以顯示最新的5~10部電影。p1
2. 身為一個電影愛好者，我希望顯示的最新5~10部電影，點下去後會秀出該電影的簡介，例如: 劇情簡介、預告片、電影時長等。p2
3. 身為一個鬼片愛好者，我希望主頁可以有分類按鈕，按下去就會顯示最新的5\~10部該類型電影，例如: 點下"鬼片"按鈕後，就會出現最新的5~10部鬼片資料。p1
4. 身為一個電影愛好者，我希望能夠有個訂閱按鈕，按下後，能夠選擇要訂閱的電影類型，只需要輸入我的手機或電子郵件，電影上映時或即將上映就會通知我。p1


### 後端
1. 身為一個管理員，我希望後台可以顯示目前訂閱人數。p2
2. 身為一個管理員，我希望能夠知道哪種電影類型最多人訂閱。p3
3. 身為一個管理員，我希望能夠定時更新最新電影資料。p1
4. 身為一個電影愛好者，我希望收到的電影通知裡，有可以取消訂閱的連結，按下後就可以取消訂閱。p1


### 技術棧
  前端-React or Next js + Styled components
  
  後端-Node + express + MongoDB
  
  主機-AWS EC2
  
  ES-LINT: airbnb 規則
  
  
  
### CSS 命名規則
kebab-case(串燒)： my-first-component; 

### JS 命名規則
camelCase(駝峰)： myFirstComponent

### 工作分配

Miaohsien: 前端-1-主頁顯示最新5\~10部電影 + 3-分類按鈕顯示最新5~10部電影

Alina: 前端-2-電影簡介 + 4-訂閱按鈕

John: 後台+後端-1-顯示訂閱人數 + 2-顯示最多人訂閱電影類型排行 + 建立電影資料爬蟲 + 建立資料庫 + 建立週期排程程式，固定週期爬電影資料放進資料庫

Jason Huang: 後端- 建立 AWS 主機 + 建立 API Server + 建立資料庫

### 動工日期
開始: 12月1日
結束: 12月22日

### 會議週期
每週三-晚上7點

### 目前進度

#### 2020/12/3

Jason Huang - [後端 API](https://github.com/JAS0NHUANG/final-project-backend)

目前開了兩個 url 分別為: http://movie-api.jas0nhuang.tw/ 以及 http://movie-api.jas0nhuang.tw/this-week
1. http://movie-api.jas0nhuang.tw/ : 得到目前上映中電影資料
2. http://movie-api.jas0nhuang.tw/this-week : 得到目前本週即將上映電影資料

Alina - [前端網頁](https://teiekinei.github.io/final-project-frontend/index.html) [前端 Repo](https://github.com/Teiekinei/final-project-frontend)
![](https://i.imgur.com/qO5Hcr4.jpg)




John - [電影資料爬蟲](https://github.com/CHANG-CHING-CHUNG/JS_Movie-crawler)
1. ![](https://i.imgur.com/7IptFRK.png)

#### 2020/12/10 進度

Alina:
* 改版面配色
* 改 Logo 加飛機特效
* 改電影介紹區塊

#### 預定工作
Jason:
* 訂閱功能
* 分享功能，例如分享到社群網站

Alina:
* 串電影簡介API
* 電影詳細資訊的 POP UP
* 網站 Footer 製作

Miaohsien:
* 網站 React 化
* 串主頁電影API 

John:
* 串 youtube 預告片



