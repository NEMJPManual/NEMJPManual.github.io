---
title: デリゲートハーベスティング
layout: default
post_number: 4
---

## デリゲート(委任)ハーベスティングの利用方法

<div style="margin:10px 0;background-color:#FAFAFA;display:inline-block;border-radius:10px;padding:10px;border:1px solid;">
  <b>このページで必要な知識</b>
  <ul>
    <li>パソコンの基本的な知識</li>
    <li>NEM基本用語</li>
    <li>NIS/NCCとlightwallet</li>
    <li>リモートNISとローカルNIS</li>
    <li>Vested Balanceについて</li>
    <li>ハーベスティングについて</li>
  </ul>
</div>

このページでは、デリゲート(委任)ハーベスティングのやり方を説明しています。

### 条件

+ Vested Balanceが10000以上のアカウントであること(詳しくは<a href="vested_balance.html">Vested Balanceについて</a>を参照。)
+ それに加え有効化する際に使用する10XEMがあること。

### 1-1, NCCを開く

まず、NCCを起動しブラウザで開き、ログインします。

### 1-2, [Delegated harvesting]ボタンをクリック

次に、右上の[Delegated harvesting]ボタンをクリックします。

<img src="/images/wallet-page.png" class="img-responsive">

### 1-3, デリゲートハーベスティングを有効にさせる

画像のような画面が出るので、

次の箇所を確認・入力して[送る]ボタンをクリックしてください。


この時、306 Unexpected errorが出る場合があることが確認されています。

解決策はわかっていないのでとりあえず×ボタンをクリックして閉じましょう。

もしその後おかしくなったらnemフォーラムやmijinフォーラム等で相談してみましょう。

<table>
<tr><td>アカウント</td><td>デリゲートハーベスティングを有効にしたいアカウント</td></tr>
<tr><td>Use minimum fee</td><td>ここにチェックが入っていれば手数料が最小で済みます。</td></tr>
<tr><td>パスワード</td><td>ウォレットのパスワードを入力してください</td></tr>
</table>

<img src="/images/wallet-page2.png" class="img-responsive">

### 1-4, およそ6時間待つ

右上の[Delegated harvesting]ボタンの横に「Activating delegated harvesting...」と表示され、

取引履歴に、緑のアイコンのメッセージ・残高が n/a となっている取引が表示されます。

この取引の承認数が360 (およそ6時間かかります)になるとデリゲートハーベスティングが有効になります。

<img src="/images/wallet-page3.png" class="img-responsive">

### 1-5, デリゲートハーベスティングを開始させる

有効にしても、開始させなければ意味がありません。

「現在の残高」の下に表示されているVested Balanceが10000以上であることを確認し、

[Start delegated harvesting]ボタンをクリックしてください。

(「ハーベスティングを開始する」のままの場合、アカウント名右の下矢印から更新するをクリックして更新をしてみましょう。それでもダメならNCCを再起動してください)

次に、出てきた画面にパスワードを入力し、[開始]ボタンをクリックします。

もし、ここでエラー699が出た場合、そのNISでデリゲートハーベスティング定員に達しています

<a href="">こちらを参考に</a>別のリモートNISに接続して再度試してください。

また、ここでエラー700が出た場合、残高が足りません。現在の残高の下に書かれているVested Balanceが10000にならなければ

いけません。これは残高に応じて少しずつ増えていきますので、早くやりたい場合はXEMを多めに入れておくことをおすすめします。

<img src="/images/wallet-page4.png" class="img-responsive">

<img src="/images/wallet-page5.png" class="img-responsive">

### 1-6, 完了

これで完了です。あとは放置していれば勝手に収穫をしてくれます。

左のメニューから[ハーベストされたブロック]を開けばどれだけ稼げたか確認できます。

リモートNISであれば、もうコンピューターを起動させる必要はありません。

デリゲートハーベスティングの無効化方法はこの下に書いてあります。

一時的に停止させたい、他のリモートNISに繋ぎたいなどの場合は、[Stop delegated harvesting]ボタンのクリックのみで構いません。

再開時は「1-5, デリゲートハーベスティングを開始させる」と同様です。

## [2] デリゲート(委任)ハーベスティングの無効化

ローカルハーベスティングに戻したい場合等には無効化が必要です。

### 2-1, デリゲートハーベスティングを停止させる

「1-5, デリゲートハーベスティングを開始させる」で押した[Start delegated harvesting]ボタンが、

[Stop delegated harvesting]ボタンに変わっているはずですので、これをクリックし停止させます。

おそらくこの手順を飛ばしても動くとは思いますが、ハーベスティング関連はバグが多いので念の為やっておきましょう。

### 2-2, [Delegated harvesting]ボタンをクリック

右上の[Delegated harvesting]ボタンをクリックします。

<img src="/images/wallet-page6.png" class="img-responsive">

### 2-3, デリゲートハーベスティングを無効にする

「1-3, デリゲートハーベスティングを有効にさせる」と同様に、

次の箇所を確認・入力して[送る]ボタンをクリックしてください。

<table>
<tr><td>アカウント</td><td>デリゲートハーベスティングを無効にしたいアカウント</td></tr>
<tr><td>Use minimum fee</td><td>ここにチェックが入っていれば手数料が最小で済みます。</td></tr>
<tr><td>パスワード</td><td>ウォレットのパスワードを入力してください</td></tr>
</table>

<img src="/images/wallet-page7.png" class="img-responsive">

### 2-4, 完了

取引履歴に、黄色ののアイコンで、送信者/受信者がDeactivate、メッセージ・残高が n/a となっている取引が表示されます。

この取引の承認数が360 (およそ6時間かかります)になるとデリゲートハーベスティングの無効化が確定されます。
