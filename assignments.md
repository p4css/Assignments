# Crawling news search results
* 嘗試撈取自由時報的搜尋頁面http://news.ltn.com.tw/search?keyword=%E6%9F%AF%E6%96%87%E5%93%B2 （點開第二頁比較容易看得到網址的規律性）。
* 撈取的結果應包含至少100則的新聞，儲存為一`data.frame`。用`nrow()`印出你所撈取的則數。
* 撈取的結果須包含至少標題、時間、內文欄位，請用`names()`印出你所設計的`data.frame`欄位。
* 請順便在RMD中回答，你認為撈取新聞可以做什麼樣的專案或研究？我可能可以打撈什麼類型的關鍵字（列出你認為該包含的關鍵字）來回答什麼樣的問題？例如：我想撈「中國」、「台灣」這樣的關鍵字來觀察近幾年來新聞在談論中國或台灣時，其用字有何改變？而中國或台灣又有哪些相關新聞越來越受重視？可否從新聞用字發覺近期民眾對中國與台灣的感受或意識形態。
* 嘗試即可，請勿以爬蟲大量下載，避免造成對方服務塞車，影響對方權益。
