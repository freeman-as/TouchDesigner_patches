## 001_AudioViz
パーティクルを使ったビジュアライザー

---
### Tipsまとめ

- **``SOP to を使ったアトリビュート変更``**
  SOPからアトリビュートをCHOPで取り出して、
  CHOP toでSOPに戻すときに任意の値を指定することで上書きする

  ```C++
  // Note
  Circleを使ったパーティクルの発生方向を切り替えるとき、SOPの法線を位置の値に置き換えてあげれば、中心から外向きに発生するようになる
  ```




- 

------

### 使用したTouchDesginer API (抜粋)

- **``Resample (CHOP)``**
  入力チャンネルを新しいサンプル・レートやstart/end intervalに再サンプリング

  http://ted-kanakubo.com/touchdesigner-jp/?p=136
  https://docs.derivative.ca/Resample_CHOP
  https://docs.derivative.ca/ResampleCHOP_Class


- **``Shuffle (CHOP)``**
  複数入力チャンネルサンプルを1組のチャンネルサンプルに再編成

  http://ted-kanakubo.com/touchdesigner-jp/?p=128
  https://docs.derivative.ca/Shuffle_CHOP
  https://docs.derivative.ca/ShuffleCHOP_Class



- **``Pattern (CHOP)``**
  時間（秒またはフレーム）の参照を持たないサンプル配列を作成

  http://ted-kanakubo.com/touchdesigner-jp/?p=1164
  https://docs.derivative.ca/Pattern_CHOP
  https://docs.derivative.ca/PatternCHOP_Class



- **``Stretch (CHOP)``**
  チャンネルの形状を保存しながら、新しいインターバルへチャンネルを再サンプリング

  http://ted-kanakubo.com/touchdesigner-jp/?p=126
  https://docs.derivative.ca/Shuffle_CHOP
  https://docs.derivative.ca/ShuffleCHOP_Class



- **``Lookup (CHOP)``**
  ルックアップ・テーブルを参照して値を出力

  http://ted-kanakubo.com/touchdesigner-jp/?p=25
  https://docs.derivative.ca/Lookup_CHOP
  https://docs.derivative.ca/LookupCHOP_Class



- **``Cache (TOP)``**
  イメージをキャッシュ保存

  http://ted-kanakubo.com/touchdesigner-jp/?p=233
  https://docs.derivative.ca/Cache_TOP
  https://docs.derivative.ca/CacheTOP_Class



- **``Cache Select (TOP)``**
  Cache TOPからイメージを取得

  http://ted-kanakubo.com/touchdesigner-jp/?p=234
  https://docs.derivative.ca/Cache_Select_TOP
  https://docs.derivative.ca/CacheselectTOP_Class



- **``Reorder (TOP)``**
  複数の入力チャネルからRGBAを任意に選択して出力

  http://ted-kanakubo.com/touchdesigner-jp/?p=197
  https://docs.derivative.ca/Reorder_TOP
  https://docs.derivative.ca/ReorderTOP_Class



- 

------

### ショートカット

#### [ノード関連]

- 

------

### メモ

- 