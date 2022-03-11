# ccz
曹操傳到手機端的移植

這是使用 cc game editor 移植的曹操傳，遊戲將運行在 cc game player 上，此外本項目也可以作爲 cc game editer 的官方示例參考

* [cc game player](#cc_game_player)
* [cc game editor](#cc_game_editor)
* [why](#why)
* [項目結構](#項目結構)

# cc_game_player

cc game player 是一個戰旗遊戲運行平臺，其受到了曹操傳 和其 mod 的啓發，目的在於爲曹操傳及其 mod 提供一個跨平臺的運行環境，以便方便的將其部署到不同平臺上遊玩。

目前 cc game player 尚處於內部初始階段，等一切就緒後預計會以免費 app 的形式上架到 google play store，以便和本喵一樣的曹操傳愛好者可以使用 android 手機玩曹操傳。後續將依據 cc game player 的受歡迎程度決定是否發佈到其它平臺(畢竟本喵一個人又沒有資金援助，不想做太多費力而不討好的工作)

# cc_game_editor 
cc game editor 是一個 android app 讓你可以使用 android 作爲遊戲開發工具，無需編程即可爲 cc game player 平臺開發遊戲。其實更準確的說法是 cc game player 是一個沒有包含任何本體內容的遊戲，cc game editor 是官方爲 player 推出的一個 mod 製作工具，只是此 mod 工具很靈活以至於遊戲的所有內容都可以由其編輯定義。

目前 cc game editor 尚處於內部初始階段，等一切就緒後預計會以免費 app 的形式上架到 google play store，以便和本喵一樣的 曹操傳mod 愛好者可以使用 android 手機開發 曹操傳mod。後續將依據 cc game editor 和 player 的受歡迎程度決定是否發佈到其它平臺(畢竟本喵一個人又沒有資金援助，不想做太多費力而不討好的工作)

# why
[三國志曹操傳](https://zh.wikipedia.org/zh/%E4%B8%89%E5%9C%8B%E5%BF%97%E6%9B%B9%E6%93%8D%E5%82%B3) 是光榮公司1999年發佈的一款經典戰旗遊戲，手機很適合玩戰旗遊戲然而目前此類遊戲並不流行於是本喵決定將其移植到手機上來玩。

# 項目結構

* assets
    * avatar 包含所有頭像資源
    * map 所有戰鬥地圖
    * terrain 地形數據
    * theater 劇場舞臺
    * props 劇場對象圖像資源
    * object 劇場對象定義
    * scripts 劇本

