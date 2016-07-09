# NEMの説明書

## マニュアルの追加の仕方

### それぞれのファイルの追加の場所

 + 画像 -> `images/`
 * script -> `js/`
 + css -> `css/`
 + font -> `fonts/`

### `_pages/` 内に、 `xxx.md` を作る

```
$ touch _pages/xxx.md
```

`_pages/xxx.md` を作ることで `_site/xxx.html` が自動生成されます。

### 以下の内容を`xxx.md`の頭に記述

```
---
title: あばうと
layout: default
post_number: 0
---
## 設定の仕方

内容
```

### 残りを記述

html と markdown の記法両方使えます。
