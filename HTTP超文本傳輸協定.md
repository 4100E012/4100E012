HTTP
(https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)
超文本傳輸協議
(https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)
HTTP是一種用於分佈式、協作式和超媒體訊息系統的*應用層*協定




*HTTP Request method請求方法*
(https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)
HTTP/1.1協定中共定義了八種方法（也叫「動作」）來以不同方式操作指定的資源：

GET        使用GET方法應該只用在讀取資料
HEAD       與GET方法一樣，都是向伺服器發出指定資源的請求。只不過伺服器將不傳回資源的本文部份。它的好處在於，使用這個方法可以在不必傳輸全部內容的情況下，就可以取得其中「關於該資源的訊息」（元訊息或稱元資料）。
POST       向指定資源提交資料，請求伺服器進行處理（例如提交表單或者上傳檔案）。資料被包含在請求本文中。
PUT        向指定資源位置上傳其最新內容。
DELETE     請求伺服器刪除Request-URI所標識的資源。
TRACE      回顯伺服器收到的請求，主要用於測試或診斷。
OPTIONS    這個方法可使伺服器傳回該資源所支援的所有HTTP請求方法。
CONNECT    HTTP/1.1協定中預留給能夠將連接改為隧道方式的代理伺服器。通常用於SSL加密伺服器的連結（經由非加密的HTTP代理伺服器）。
