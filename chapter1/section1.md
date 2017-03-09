# html

## 是什麼?
是一種用於建立網頁的標準標示語言。

特徵是巢狀結構，並以<>包覆，</>結尾

    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <title></title>
      </head>
      <body>

      </body>
    </html>

此段程式碼則為html的基本架構

## html5又是?

自1999年來一直使用的是html4，終於在2014制定了新的html5。簡單來說跟之前的差異主要是增加了語意化的標籤及與多媒體(不用依賴flash)、繪圖(canvas)功能。

html4

    <div class="header">
      <div class="nav">
        <ol>
          <li>選單1</li>
          <li>選單2</li>
          <li>選單3</li>
        </ol>
      </div>
    </div>

html5

    <header>
      <nav>
        <ol>
          <li>選單1</li>
          <li>選單2</li>
          <li>選單3</li>
        </ol>
      </nav>
    </header>


## 開發環境
建議找個好用的文字編輯器，不過你要用記事本、vi寫我也是沒意見

1. [Atom](https://atom.io/)
2. [Visual Studio Code](https://code.visualstudio.com/)
3. [Sublime text](https://www.sublimetext.com/)

## 動手！
用幾種標籤來試著寫看看html吧

### `<p>`
為文章的一個段落

    <p>第一行</p>
    <p>第二行</p>

### `<input>`
為最基礎的輸入框框。

    <input>

<input placeholder="試試看吧">

其中在標籤名稱空格，稱為屬性，可產生不同變化。

    <input type="password">

<input type="password" value="123456">

例如這麼做就會產生密碼的input物件

### `<img>`
插入圖片的標籤，注意要給他src的屬性指向圖片位置，不然是無法顯示的

    <img src="nyan-cat.jpg">

<img src="nyan-cat.jpg">

### `<ol> & <li>`
常見的序列標籤。

    <ol>
      <li>a</li>
      <li>b</li>
      <li>c</li>
    </ol>

<ol>
  <li>a</li>
  <li>b</li>
  <li>c</li>
</ol>
