## 請解釋後端與前端的差異。

1. 什麼是前端？
前端在網頁上面也可以說是「看得見的部分」，舉凡一個網頁的版面、圖片、按鈕或者連結可以執行一些動作的，都屬於前端的範圍。

2. 什麼是後端？
資料管理、數據之類的就叫做後端，像是登入之後的會員資料，在網站上買東西的訂單內容，都屬於後端的範圍。

3. 前後端差異：
使用者介面歸類在前端，伺服器、應用程式、資料庫則屬於後端。
一個網站的運行，不只是仰賴前端或者後端，它們的關係就像是汽車跟汽油、唇齒相依，如影隨形，缺一不可，手牽手心連心，等一下要去看初音。

## 假設我今天去 Google 首頁搜尋框打上：JavaScript 並且按下 Enter，請說出從這一刻開始到我看到搜尋結果為止發生在背後的事情。

當我們在瀏覽器上面搜尋時，瀏覽器會發送請求（request）到伺服器上;伺服器再發送請求到資料庫，接著資料庫回傳資料到伺服器（response），伺服器再回傳這些資料到瀏覽器上面，然後你就得到你搜尋的資料了。

Chrome reqeust -> server reqeust -> database;
Database response -> server response -> chrome


## 請列舉出 3 個「課程沒有提到」的 command line 指令並且說明功用

1. cp: 複製檔案，例如 `cp test test1` 就是複製 test 這個檔案，並把它取名為 test1
2. find: 尋找資料夾，例如 `find 接資料夾名稱`
3. head: 列出檔案的第一行，例如 `head 檔案名稱` 