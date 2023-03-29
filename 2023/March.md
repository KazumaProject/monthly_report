## 取り組んだこと

1. Android の Markdown の補助キーボードアプリの作成

## 取り組んだ理由

Rails の勉強と並行してアプリの作成をしようと考えたが先にアプリを作ってからの方が勉強に集中できると考えた為。
結果として最終課題でやりたい事の方向性が見えたので良かったと思っている。
今はリリースできる品質まで作り上げたいと思っている。

## 実装したこと

<img src="https://github.com/KazumaProject/monthly_report/blob/master/images/test_1.gif" width="412" height="892" />

1. キーボードの View

2. 文字の予測変換

3. 入力中の文字の操作

### キーボードの View

日本語、英語と数字のモードがある。
テンキーのレイアウトを採用した。
QWERTY はまた後日実装したい。

### 文字の予測変換

日本語のかな漢字変換機は [Openwnn](https://github.com/MozillaReality/OpenWnn) を利用した。

### 入力中の文字の操作

キーボードの動作は Google Japanese Input を参考にした。

## 今後実装すること

1. アルファベットと数字の入力

2. 英語の変換器 (可能なら)

3. 記号や絵文字の View を作成してそこに Markdown の補助も追加する

## 総括

アプリは4月中にリリースできるように取り組んでいる。

