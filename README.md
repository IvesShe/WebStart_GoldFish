# 金魚都能懂 網頁設計筆記

實作練習筆記，也方便之後參考

# 線上DEMO

https://ivesshe.github.io/WebStart_GoldFish/

# normalize

作部分的初始化

https://necolas.github.io/normalize.css/

```css
/*! normalize.css v8.0.1 | MIT License | github.com/necolas/normalize.css */

/* Document
   ========================================================================== */

/**
 * 1. Correct the line height in all browsers.
 * 2. Prevent adjustments of font size after orientation changes in iOS.
 */

html {
  line-height: 1.15; /* 1 */
  -webkit-text-size-adjust: 100%; /* 2 */
}

/* Sections
   ========================================================================== */

/**
 * Remove the margin in all browsers.
 */

body {
  margin: 0;
}

/**
 * Render the `main` element consistently in IE.
 */

main {
  display: block;
}

/**
 * Correct the font size and margin on `h1` elements within `section` and
 * `article` contexts in Chrome, Firefox, and Safari.
 */

h1 {
  font-size: 2em;
  margin: 0.67em 0;
}

/* Grouping content
   ========================================================================== */

/**
 * 1. Add the correct box sizing in Firefox.
 * 2. Show the overflow in Edge and IE.
 */

hr {
  box-sizing: content-box; /* 1 */
  height: 0; /* 1 */
  overflow: visible; /* 2 */
}

/**
 * 1. Correct the inheritance and scaling of font size in all browsers.
 * 2. Correct the odd `em` font sizing in all browsers.
 */

pre {
  font-family: monospace, monospace; /* 1 */
  font-size: 1em; /* 2 */
}

/* Text-level semantics
   ========================================================================== */

/**
 * Remove the gray background on active links in IE 10.
 */

a {
  background-color: transparent;
}

/**
 * 1. Remove the bottom border in Chrome 57-
 * 2. Add the correct text decoration in Chrome, Edge, IE, Opera, and Safari.
 */

abbr[title] {
  border-bottom: none; /* 1 */
  text-decoration: underline; /* 2 */
  text-decoration: underline dotted; /* 2 */
}

/**
 * Add the correct font weight in Chrome, Edge, and Safari.
 */

b,
strong {
  font-weight: bolder;
}

/**
 * 1. Correct the inheritance and scaling of font size in all browsers.
 * 2. Correct the odd `em` font sizing in all browsers.
 */

code,
kbd,
samp {
  font-family: monospace, monospace; /* 1 */
  font-size: 1em; /* 2 */
}

/**
 * Add the correct font size in all browsers.
 */

small {
  font-size: 80%;
}

/**
 * Prevent `sub` and `sup` elements from affecting the line height in
 * all browsers.
 */

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sub {
  bottom: -0.25em;
}

sup {
  top: -0.5em;
}

/* Embedded content
   ========================================================================== */

/**
 * Remove the border on images inside links in IE 10.
 */

img {
  border-style: none;
}

/* Forms
   ========================================================================== */

/**
 * 1. Change the font styles in all browsers.
 * 2. Remove the margin in Firefox and Safari.
 */

button,
input,
optgroup,
select,
textarea {
  font-family: inherit; /* 1 */
  font-size: 100%; /* 1 */
  line-height: 1.15; /* 1 */
  margin: 0; /* 2 */
}

/**
 * Show the overflow in IE.
 * 1. Show the overflow in Edge.
 */

button,
input { /* 1 */
  overflow: visible;
}

/**
 * Remove the inheritance of text transform in Edge, Firefox, and IE.
 * 1. Remove the inheritance of text transform in Firefox.
 */

button,
select { /* 1 */
  text-transform: none;
}

/**
 * Correct the inability to style clickable types in iOS and Safari.
 */

button,
[type="button"],
[type="reset"],
[type="submit"] {
  -webkit-appearance: button;
}

/**
 * Remove the inner border and padding in Firefox.
 */

button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
  border-style: none;
  padding: 0;
}

/**
 * Restore the focus styles unset by the previous rule.
 */

button:-moz-focusring,
[type="button"]:-moz-focusring,
[type="reset"]:-moz-focusring,
[type="submit"]:-moz-focusring {
  outline: 1px dotted ButtonText;
}

/**
 * Correct the padding in Firefox.
 */

fieldset {
  padding: 0.35em 0.75em 0.625em;
}

/**
 * 1. Correct the text wrapping in Edge and IE.
 * 2. Correct the color inheritance from `fieldset` elements in IE.
 * 3. Remove the padding so developers are not caught out when they zero out
 *    `fieldset` elements in all browsers.
 */

legend {
  box-sizing: border-box; /* 1 */
  color: inherit; /* 2 */
  display: table; /* 1 */
  max-width: 100%; /* 1 */
  padding: 0; /* 3 */
  white-space: normal; /* 1 */
}

/**
 * Add the correct vertical alignment in Chrome, Firefox, and Opera.
 */

progress {
  vertical-align: baseline;
}

/**
 * Remove the default vertical scrollbar in IE 10+.
 */

textarea {
  overflow: auto;
}

/**
 * 1. Add the correct box sizing in IE 10.
 * 2. Remove the padding in IE 10.
 */

[type="checkbox"],
[type="radio"] {
  box-sizing: border-box; /* 1 */
  padding: 0; /* 2 */
}

/**
 * Correct the cursor style of increment and decrement buttons in Chrome.
 */

[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
  height: auto;
}

/**
 * 1. Correct the odd appearance in Chrome and Safari.
 * 2. Correct the outline style in Safari.
 */

[type="search"] {
  -webkit-appearance: textfield; /* 1 */
  outline-offset: -2px; /* 2 */
}

/**
 * Remove the inner padding in Chrome and Safari on macOS.
 */

[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}

/**
 * 1. Correct the inability to style clickable types in iOS and Safari.
 * 2. Change font properties to `inherit` in Safari.
 */

::-webkit-file-upload-button {
  -webkit-appearance: button; /* 1 */
  font: inherit; /* 2 */
}

/* Interactive
   ========================================================================== */

/*
 * Add the correct display in Edge, IE 10+, and Firefox.
 */

details {
  display: block;
}

/*
 * Add the correct display in all browsers.
 */

summary {
  display: list-item;
}

/* Misc
   ========================================================================== */

/**
 * Add the correct display in IE 10+.
 */

template {
  display: none;
}

/**
 * Add the correct display in IE 10.
 */

[hidden] {
  display: none;
}
```


# reset.css

完全初始化

https://meyerweb.com/eric/tools/css/reset/

```css
/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
```

# 排個稀飯版 

[排個稀飯版](./webDemo/20.html)

![image](./images/Xnip2022-07-09_17-33-40.jpg)

![image](./images/Xnip2022-07-09_17-33-47.jpg)

# Transition 網頁動畫 

[Transition 網頁動畫](./webDemo/21.html)

![image](./images/Xnip2022-07-10_11-10-09.jpg)

```css
.btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: #000;
    text-decoration: none;
    color: #fff;
    /* transition: 屬性 轉換時間 延遲執行時間 速度; */
    transition: padding 1s 0s ease, background-color 1s 1s;
  }

  .btn:hover {
    background-color: #f00;
    color: #ff0;
    padding: 10px 30px;
  }
```

```html
<a href="#" class="btn">送出</a>

```

# Animation 網頁動畫

[Animation 網頁動畫](./webDemo/22.html)

![image](./images/Xnip2022-07-10_11-10-50.jpg)

```css
.box {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  background-color: #f00;
}

.box1 {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  background-color: #f00;
  /* animation: 動畫名稱 播放時間 延遲執行的時間 速度 次數 方向 填充模式 播放狀態; */
  animation: ives 1s infinite alternate;
}

@keyframes ives {
  0% {
    border-radius: 50%;
  }

  100% {
    border-radius: 0%;
  }
}
```

```html
<div class="box"></div>
<div class="box1"></div>

```

# 媒體查詢

## [媒體查詢](./webDemo/23.html)

![image](./images/Xnip2022-07-10_11-11-04.jpg)

![image](./images/Xnip2022-07-10_11-11-10.jpg)

```css
.ives {
  width: 100%;
  height: 300px;
}

.ives1 {
  background-color: #faa;
}

.ives2 {
  background-color: #aaf;
}

@media screen and (min-width:768px) {
  .ives {
    width: 50%;
    float: left;
  }
}
```

```html
<div class="ives ives1">ives1</div>
<div class="ives ives2">ives2</div>

```

## [媒體查詢23-1](./webDemo/23-1.html)

![image](./images/Xnip2022-07-10_11-13-54.jpg)

![image](./images/Xnip2022-07-10_11-11-31.jpg)

```css
.ives {
  width: 100%;
  height: 300px;
  display: none;
}

@media screen and (min-width:768px) {
  .ives {
    background-color: #f00;
    display: block;
  }
}

@media screen and (min-width:1200px) {
  .ives {
    background-color: #00f;
    display: block;
  }
}
```

```html
<div class="ives ives1">ives1</div>

```

# RWD入門

[RWD入門](./webDemo/24.html)

![image](./images/Xnip2022-07-10_11-29-45.jpg)

![image](./images/Xnip2022-07-10_11-29-53.jpg)

# RWD試排版

[RWD試排版](./webDemo/25.html)

![image](./images/Xnip2022-07-10_12-10-11.jpg)

![image](./images/Xnip2022-07-10_12-10-23.jpg)

# RWD選單製作

## [RWD選單製作](./webDemo/26.html)

![image](./images/Xnip2022-07-10_12-58-53.jpg)

![image](./images/Xnip2022-07-10_12-58-37.jpg)

## [RWD選單製作02](./webDemo/26-1.html)

![image](./images/Xnip2022-07-10_12-55-15.jpg)

![image](./images/Xnip2022-07-10_12-56-48.jpg)


# Bootstrap 入門

```
預設 .col-2
手機 直 .col-佔欄數
手機 橫 .col-sm-佔欄數

平板 直 .col-md-佔欄數
平板 橫 .col-lg-佔欄數

桌機 .col-xl-佔欄數

```
[Bootstrap 入門](./webDemo/27.html)

![image](./images/Xnip2022-07-10_18-03-54.jpg)

![image](./images/Xnip2022-07-10_18-03-43.jpg)

# Bootstrap 組件入門

[Bootstrap 組件入門](./webDemo/28.html)

![image](./images/Xnip2022-07-11_11-35-16.jpg)

![image](./images/Xnip2022-07-11_11-35-08.jpg)

# JQuery入門

https://jquery.com/

![image](./images/Xnip2022-07-11_11-42-04.jpg)

[JQuery入門](./webDemo/29.html)

# JQuery事件

[JQuery事件](./webDemo/30.html)

![image](./images/Xnip2022-07-11_15-25-22.jpg)

[JQuery事件](./webDemo/30-1.html)

![image](./images/Xnip2022-07-11_15-33-32.jpg)

# JQuery CSS控制

[CSS控制](./webDemo/31.html)

![image](./images/Xnip2022-07-11_16-42-32.jpg)

[CSS控制 02](./webDemo/32.html)

![image](./images/Xnip2022-07-11_16-41-13.jpg)

# JQuery動畫

[JQuery動畫](./webDemo/33.html)

![image](./images/Xnip2022-07-11_16-53-11.jpg)

[JQuery動畫 02](./webDemo/34.html)

![image](./images/Xnip2022-07-11_16-52-50.jpg)


# 參考資料

https://www.youtube.com/watch?v=ZavL9y4Adrk&list=PLqivELodHt3iL9PgGHg0_EF86FwdiqCre&index=1&t=3s&ab_channel=CSScoke

https://ithelp.ithome.com.tw/articles/10202562

http://localhost:5500/webDemo/28.html
