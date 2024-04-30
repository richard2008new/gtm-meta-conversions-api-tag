# GTM Meta Conversion API Tag


這是一個非官方的Facebook CAPI標籤,用於Google Tag Manager社群模板庫。如果您發現任何錯誤或有任何疑問,請提出問題!


這是您的 GTM Web Container 的轉換API觸發代碼, 用於數據並將其發送到 ftargeting server。


### Pixel ID


這是Facebook Pixel ID,可以在Facebook Business Manager中找到。


### Event Name


您想要使用此標籤來測量的事件。Facebook使用一組標準事件。如果標準事件無法滿足您的需求,您也可以使用自定義事件名稱。


### Anonymise IP address


將aip參數發送到伺服器端解決方案,從而丟棄遠端IP地址,不會將其發送到Facebook。


### Anonymise user agent


將aua參數發送到伺服器端解決方案,從而丟棄用戶代理,不會將其發送到Facebook。


### Object Properties


您可以在任何事件中包含物件屬性。


#### Object Properties Variable


您可以使用返回Object的變數來包含物件屬性。任何其他類型都將被丟棄。這在您需要在某些頁面上包含產品數據時很有用,只需在產品頁面上返回您需要的值,在其餘頁面上返回undefined即可。


#### Object Properties Table


除了變數之外,您還可以使用表格來包含物件屬性。請注意,如果有任何重複的鍵,物件屬性表將覆蓋來自物件屬性變數的值。


### Optional Parameters


#### Event ID


Facebook Pixel 和 CAPI使用事件ID來去重複傳送的事件。


### User Data


用來傳送使用者 email 和 phone。
