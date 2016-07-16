---
title: VestedBalanceについて
layout: default
post_number: 3
---

## VestedBalanceについて

<div style="margin:10px 0;background-color:#FAFAFA;display:inline-block;border-radius:10px;padding:10px;border:1px solid;">
<b>このページで必要な知識</b>
<ul>
  <li>パソコンの基本的な知識</li>
</ul>
</div>

このページでは、Vested Balanceを説明しています。

## 概要

NEMにはBalance(残高)ともうひとつ、Vested Balance(直訳すると既得残高)というものがあります。

ハーベスティングを行うにはこのVested Balanceが10,000以上にならなければなりません。

## 説明

### 簡単な説明

Vested Balanceは、1440ブロック(およそ1日)毎に **(Balance - Vested Balance) × 0.1** づつ増えていきます。

<blockquote cite="http://nem.io/NEM_techRef.pdf">
<img src="/images/gaining-vested-balance.png" class="img-responsive">
</blockquote>

http://nem.io/NEM_techRef.pdf NEM referenceより引用

上の画像は、100,000XEM入金した際の、Vested balanceの増え方を表しています。

これが入金額と同じ100,000になるには途方もない時間がかかることは容易に想像できます。

ですから、ハーベスティング目的でXEMを保有する際は、10,000XEM丁度ではなく、多めに購入することをおすすめします。

次の画像のグラフは、XEM入金量とVested Balanceが10,000以上になる日数の関係をあらわしたものです。

(上の画像ははXEM入金量が10,000~110,000の場合、下の画像は上の画像のグラフを15,000~110,000の範囲で拡大したものです。)

実際の計算方法とは異なる可能性があるので、目安としてお使いください。

<img src="/images/amount-of-xem.png" class="img-responsive">

<img src="/images/amount-of-xem2.png" class="img-responsive">

### なんでこんなめんどくさいのか

簡単にいうと大量のハーベスティング目的のアカウント(所謂副垢)を作らせないためです。

１つハーベスティング用のアカウントを作るのに、多くの時間またはお金を掛けさせることにより、大量に作ることを困難にさせています。

そうすることでネットワークが安定するそうです。
