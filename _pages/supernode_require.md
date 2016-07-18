---
title: スーパーノードの必要条件
layout: default
post_number: 6
---

## スーパーノードの必要条件

<table cellpadding="10" cellspacing="0" border="1" bordercolor="#6a95c7">
  <tr>
    <th>テスト項目</th>
    <th>要求</th>
    <th>備考</th>
  </tr>
  <tr style="background-color:#d3dfee;">
    <th>帯域幅</th>
    <td>5000kbpsあるいはそれ以上</td>
    <td>3ノードから平均2MBがダウンロードされます。</td>
  </tr>
  <tr>
    <th>チェーンの高さ</th>
    <td>同期されている必要があります。</td>
    <td>4ブロック以上遅れてはいけません。</td>
  </tr>
  <tr style="background-color:#d3dfee;">
    <th>チェーン部分</th>
    <td>正確なチェーンの一部50ブロックをアップロードすること</td>
    <td>ノードからダウンロードされたハッシュは、正確性の基準となるチェーンと比較されます。</td>
  </tr>
  <tr>
    <th>計算速度</th>
    <td>最低秒間2000回繰り返しハッシュができること</td>
    <td>ノードは、32バイトシードの10000回繰り返し計算するように求められます。スピードと最終的な精度が測定されます。</td>
  </tr>
  <tr style="background-color:#d3dfee;">
    <th>保証金</th>
    <td>3,000,000XEM</td>
    <td>ノードは、300万XEMを保有するアカウントのデリゲートキーで起動する必要があります。</td>
  </tr>
  <tr>
    <th>NISのバージョン</th>
    <td>最新であること</td>
    <td>管理者はすぐにアップデートするべきです</td>
  </tr>
  <tr style="background-color:#d3dfee;">
    <th>Ping</th>
    <td>200ms以下</td>
    <td>他のすべてのノードに収集されたPingのうち、少なくとも一つは試験に合格しなければなりません。</td>
  </tr>
  <tr>
    <th>応答性</th>
    <td>ノードは10回の連続したブロックチェーンの高さリクエストに応答する必要があります。</td>
    <td>少なくとも9つのリクエストへの応答の時間が全体でほぼ1秒であれば合格することができます。</td>
  </tr>
</table>

**これ以外にもセキュリティ対策は万全を期すように!スーパーノードはNEMの安全と安定性を担保するためのノードです。不特定多数の人が利用します。その運営者である自覚を持ちましょう。**


元画像 https://forum.nem.io/t/nem-supernode-rewards-program/1735 より引用

<img src="/images/super-node-req.png" class="img-responsive">
