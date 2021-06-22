# CS381
PCHOME線上購物爬蟲
# 簡短介紹
此程式是用Python，透過API來擷取PCHOME的資料，達到快速搜尋的效果。
# 使用介紹
使用方式非常簡單，只要在main Function裡，先執行search_products，即可得到商品的各種資料，再用其資料來搜尋更詳細的資料。
圖片
# 實作介紹
因PCHOME的介面較為複雜，有許多分類可以點選，因此設置了許多不同功能的Function，來執行網頁上相對應的功能，像是搜尋商品、商品狀態、商品分類等等。
### User-Agent
開始搜尋之前記得先加User-Agent，避免程式發生錯誤
![image](https://github.com/kzn641/1071816/blob/main/useragent.PNG)
### Get
使用Get套件來擷取資料
![image](https://github.com/kzn641/1071816/blob/main/get.PNG)
### 搜尋商品
將回傳的對應參數做設定，來達到在網頁相同功能的作用
參數圖片
![image](https://github.com/kzn641/1071816/blob/main/%E5%95%86%E5%93%81%E5%88%86%E9%A1%9E.PNG)
### 商品狀態
取得商品販售狀態
參數: *ButtonType*:商品是否還有貨、*ForSale*:商品有出售、可以購買、*SoldOut*:商品已售完
![image](https://github.com/kzn641/1071816/blob/main/%E5%95%86%E5%93%81%E7%8B%80%E6%85%8B.PNG)
### 商品分類
取得商品分類狀態
參數: *Id*:商品id、*name*:商品名稱、*qty*:商品數量
![image](https://github.com/kzn641/1071816/blob/main/%E5%95%86%E5%93%81%E5%88%86%E9%A1%9E.PNG)
# 參考
* Item 1 https://blog.jiatool.com/posts/pchome_spider01/#%E5%9B%9E%E5%82%B3%E8%B3%87%E6%96%99
