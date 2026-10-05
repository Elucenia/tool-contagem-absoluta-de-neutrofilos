<!-- ELUCENIA technical documentation · contagem-absoluta-de-neutrofilos · ja · no clinical/professional/rights approval -->

# 好中球絶対数

[条件・出典・許諾](https://elucenia.org/ja/tools/contagem-absoluta-de-neutrofilos)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 総白血球数

`leuco`

/µL · 範囲: 10–500000

### 分葉核好中球

`seg`

% · 範囲: 0–100

### 桿状核好中球（任意）

`bast`

% · 任意 · 範囲: 0–100

## 方法の版

ANC：白血球×(分葉核+桿状核)/100；IDSA 2010更新/2011公表の文脈

## 記載された計算式

好中球絶対数 = 白血球（/µL）×（分葉核好中球% + 桿状核好中球%）÷100.

## 限界・対象集団

IDSA 2010/2011の文献は、がん患者の化学療法に起因する発熱と好中球減少を扱い、徴候・症状、がん、治療、併存疾患に応じてリスクを層別化しています。絶対数の計算値は、この評価に代わるものではありません。定義の閾値と単位はガイドライン全文で確認する必要があり、今回読んだ抄録には記載されていません。

## 参考文献

- [Freifeld AG et al. Clinical practice guideline for the use of antimicrobial agents in neutropenic patients with cancer: 2010 update by the Infectious Diseases Society of America. Clin Infect Dis, 2011.](https://doi.org/10.1093/cid/cir073)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
