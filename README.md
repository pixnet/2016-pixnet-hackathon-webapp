<center><h1> Mobile App / Web Service </h1></center>
----
全球最大華文個人媒體聯盟「痞客邦 PIXNET」旗下產品包含全台最大社群服務 <痞客邦> 以及全台最具影響力的美妝時尚社群 <styleMe>，擁有大量優質的 UGC (User Generated Content) 內容。今年，除了大眾熟知的吃喝玩樂內容，「痞客邦 PIXNET」將開放豐富的時尚、美妝的精彩元素，期待鼓勵參賽者能夠有更多創新的發想。

### 資料說明
----
* 分類熱門照片
  * 資料簡介：全站相簿內容分類涵蓋極廣，譬如：國內外旅遊、美食紀錄、親子、攝影...等，這份資料包含各分類的熱門照片詳細資料，以使用者權限設定「完全公開」為前提，並且含有 EXIF 以及位置(經緯度)資料為限。（提供照片***色碼***資訊，為顏色佔圖片比例，提供前 64 色。）
  * 資料範圍：包含24個分類，約18萬筆資料。
  * [資料細部](./01_hot_picture/01_data_schema.md)
  * [資料範例](./01_hot_picture/01_sample.json)
  * 完整資料集會再以 Mail 通知
* 時尚、美妝部落客及文章
  * 資料簡介：時尚、美妝相關內容近來在「痞客邦PIXNET」有蓬勃發展的趨勢，且另外創立 &lt;styleMe&gt; ，此資料集中，整理了包含時尚美妝類的：「部落格清單」、「最新文章內容」、「影響力百大內容創作者」，此外還可搭配分類熱門照片中的時尚美妝類照片，做出各種搭配應用。
  * 資料範圍：1萬個熱門部落格，30多萬篇精選文章，以及PIXNET[百大社群影響力](https://blogranking.events.pixnet.net/)部落客名單。
  * [資料細部](./02_fashion_and_beauty/02_data_schema.md)
  * [資料範例1](./02_fashion_and_beauty/02_blog_list_sample.json)、[資料範例2](./02_fashion_and_beauty/02_article_sample.json)、[資料範例3](./02_fashion_and_beauty/02_top_author_sample.json)
  * 完整資料集會再以 Mail 通知
* 分類熱門地點相關文章
  * 資料簡介：選取全站15個與地理位置較相關的分類(ex.  美食, 活動, 親子...等)，擷取各分類的熱門地點所對應的相關文章。
  * 資料範圍：包含15個分類，約10萬筆文章內容及相關資料。
  * [資料細部](./03_hot_location_article/03_data_schema.md)
  * [資料範例](./03_hot_location_article/03_sample.json)
  * 完整資料集會再以 Mail 通知
* PIXNET Open API
  * 資料簡介：所有公開資料不需要認證即可存取；而要操作私人資訊（例如發表文章）則需要使用 OAuth 做認證，你可以透過報名時填寫的 API Key 存取 PIXNET API 而不受存取次數限制，至於 API 可到開發網站上申請。
  * [API鏈結](https://developer.pixnet.pro/)

### 評分標準
---
評分主要跟據三個不同面相，由專業評審做最終判斷。
- 資料利用度：了解資料意涵、充分運用提供資料特性。
- 創意綜合評估：應用能否讓現場觀眾評審驚艷，留下深刻印象及反應。
- 整體完成度：Demo 順暢程度、是否有完整的 User Story。

### 相關參考資料
----
- JSON 格式請參考 http://json.org/
- GeoJSON 格式請參考 http://geojson.org/
- 相簿、部落格分類的ID對應
  - 相簿分類 https://developer.pixnet.pro/#!/doc/pixnetApi/mainpageAlbumCategories
  - 文章分類 https://developer.pixnet.pro/#!/doc/pixnetApi/mainpageBlogCategories
  - 部落格分類 https://developer.pixnet.pro/#!/doc/pixnetApi/blogSiteCategories



