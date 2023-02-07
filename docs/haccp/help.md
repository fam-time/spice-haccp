# SPICE for HACCP ヘルプ
- [よくある質問](faq.html)

## チュートリアル
- [はじめてのSPICE for HACCP](tutorials/1.html)

# 基本的な使い方
## 01 Nodeを作る

左側の`食材・調味料ノード`を、右側の空白領域にドラッグ＆ドロップすると、新たな食材ノードが作成されます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675687232/SPICE/010MakeNode03_o8efxe.gif">

同様の操作で操作ノードも作成することができます。

### 011 食材を記入する

食材ノードの編集状態で、食材名を入力します。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675407265/SPICE/011EditNode_sgwskz.gif">

### 012　手順ノード（＋Edge）を追加する

a.マウスで追加する方法

追加したいNodeをクリックすると、下に+アイコンが表示されるので、そのアイコンをクリックしてください。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675687260/SPICE/012a_AddActionNode02_ooaiyn.gif">

b.キーボードで追加する方法

Node編集中に`Tab`キーを押すと、`+`アイコンが黄色く表示されるので、続けて`Enter`キーを押すと、下に操作ノードが作成されます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675687267/SPICE/012b_AddActionNode02_ivqcox.gif">

---

## 02 Edgeを追加する

### 021 Edgeを追加する

Nodeを選択すると、表示される下の部分に黒い四角■部分にマウスを合わせ、`＋`印にさせ、その状態からドラッグすると、つなげられる部分が青い四角で強調表示されるので、対象までマウスをつなげるてドロップ（クリックを解除）すると、Edgeが追加されます。

<img width="400" src="https://res.cloudinary.com/fam-time/image/upload/v1675687282/SPICE/021MakeEdge02_uaila9.gif">

### 022 Edgeを削除する

削除したいEdgeの選択（クリック）すると、削除用のゴミ箱アイコンが表示されるので、クリックすると、Edgeを削除できます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675744421/SPICE/022DeleteEdge02_hieomn.gif">

### 023　Edgeの間にNodeを追加する

NodeとNodeの間のEdgeを選択し、`＋`のアイコンをクリックすると、間にNodeが追加されます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675744549/SPICE/023AddNodeBetweenEdges02_yxntve.gif">

### 024　複数の組み合わせ（NodeとEdge）をコピーする

マウスをドラッグ＆ドロップすると、複数の組み合わせ（NodeとEdge）を選択できます。
その状態で、右クリックするとメニューが表示されるのでコピーを選ぶと、その組み合わせがコピーされます。

次に適当な場所で同じく右クリックして表示されるメニューからペーストを選択すると、コピーされた組み合わせがペーストされます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675747324/SPICE/024PartsCopyPaste_sqjvfd.gif">

---

## 03 Nodeの基本情報を設定する
### 031 ノードの区域、作業エリアを設定する

Nodeを選択し、右側の`区域`を選択し、さらに`作業エリア`の中から該当する作業エリアを選択すると、左側にその内容が表示されます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675407267/SPICE/031EditArea_whvzdb.gif">

### 032 CCPを設定する

CCPのNodeを選択し、`重要管理点`を選択状態にすると、CCPとして指定されます。

指定後、`CCPテキスト`にその条件を入力すると、内容が記録できます。

左側の`CCP`をクリックすると、記載した条件が表示されます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675407263/SPICE/032EditCCP_drbirn.gif">

### 033　自動採番する

任意のNodeを選択した状態で、右側の`基本情報`タブメニューの中から、一番上のNo.の横の`全体を自動採番する`アイコンをクリックすると、全てのNodeに番号が採番されます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675407259/SPICE/033_Numbering02_pwq5s6.gif">


⚠️ 自動採番は、Nodeの位置に応じて左上から採番されます。

---

## 04　Nodeの危害要因分析を設定する

### 041　危害要因分析の入力項目【参考情報】

危害要因分析では、それぞれの工程ごとにどのような危害要因が潜んでいるのか分析します。

1. まずは工程で予測される危害要因を記載した上で、
1. その危害要因が重大かどうかチェック（Yes/No）し、
1. その判断根拠を述べた上で、
1. 重大な危害要因がYesと判断した場合はどう管理するかの手法を記載します。
1. そして、最終的に全体のプロセスの中でCCPかどうかをチェックします。


(厚生労働省HACCP導入のための手引書より引用)

### 042　危害要因分析の入力

Nodeを選択した状態で、右側のメニューから、`危害要因分析`タブを選択してください。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675745775/SPICE/042-1HATab_hng12y.png">


左側の、`危害要因を追加します`ボタンをクリックすると、入力欄が表示されます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675745775/SPICE/042-2AddHZD_w2i5on.png">

表示された入力欄に、それぞれ必要な情報を入力してください。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675745775/SPICE/042-3FillHAList_kmj0pf.png">

### 043　危害要因分析データのダウンロード

作成した危害要因分析のデータは、要因別（生物的な要因、化学的な要因、物理的な要因）

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675745775/SPICE/043DlHA_u2w9zn.png">

### 044　危害要因分析データのアップロード

一度ダウンロードした危害要因分析のデータはアップロードすることができます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675745775/SPICE/044UpHA_jiqi1l.png">

### 045　危害要因分析をExcelダウンロードする

右上のExcel↓印のアイコンをクリックすると、危害要因分析の内容をExcel形式でダウンロードすることができます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675745775/SPICE/053DlHAxls_vlpcpb.png">

---

## 05　保存と読み込み

### 051 保存する

右上の↓印のアイコンをクリックしてください。

作成したマテリアルフローのデータがダウンロードされます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675745775/SPICE/051Save_y61njg.png">

### 052 保存済みのJsonを読み込む

右上の↑印のアイコンをクリックし、描写させたいファイルを選択してください。

作成したマテリアルフローが描写されます。

<img width="300" src="https://res.cloudinary.com/fam-time/image/upload/v1675745775/SPICE/052Up_yxjttt.png">

---

以上がSPICE for HACCPの基本的な使い方です。
ご利用の中で気づいた点や、ご要望については、是非ともフィードバックください！！！