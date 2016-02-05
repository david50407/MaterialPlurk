# MaterialPlurk

嘗試在新版（2016.02.04）中融入 Google Material 的元素。

# Features

* 使用 SCSS (SASS) 撰寫，可以輕易調整屬性
* 包含編譯結果，非開發者也能自行套用樣式
* Extension 機制，就算是編譯好的 CSS，也只要透過簡單的註解開關即可輕鬆套用／取消套用，方法如下所示

# Extensions

## 開關方式

如下所示為一 Extension，其開頭結尾必包含一 `BEGIN`、`END`，如下範例所示：

```
/* Expand Timeline Control BEGIN /* */

...

/* Expand Timeline Control END */
```

預設皆為開啓狀態，只要將 `BEGIN /* */` 的最後兩個 `*/` 刪除即可關閉。
反之，加回 `*/` 即可再次開啓。

## 目前的 Extension 清單

* Expand Timeline Control / 展開河道選擇器並置於右側（如舊版畫面）
* Timeline Control Icon Only / 河道選擇器僅顯示圖示及未讀數字（隱藏文字說明）

# Todo

* 調整 Dashboard
* 調整河道
