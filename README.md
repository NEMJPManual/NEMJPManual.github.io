# NEMの説明書

## 必須環境

+ rbenv (or anyenv )
+ bundler gem

ruby のバージョンは2.2.0が設定されています。

## 環境設定

```
$ bundle install --path=vendor/bundle
$ bundle exec jekyll s -o # サーバ起動
```

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

### 画像貼るとき

<img src="/images/xxx.png" class="img-responsive">
```

### 残りを記述

post_number は、サイドバーメニューのソート用です。

記事を追加する場合は、既存の記事より大きな数字を設定してください。

html と markdown の記法両方使えます。
