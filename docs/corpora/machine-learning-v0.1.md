<!-- source: Google Drive 1QIB_ukQdA0rQ98d9LZuVKouYdsVb0h7-0xGn2W72WAc -->
# Velka機械学習コーパス v0.1


### 位置づけ
現代語基礎辞書 v2.0（907語）を用い、機械学習論文・技術報告に必要な語彙を負荷試験する
題材は架空の植物データ分類・数値予測とし、モデル構築そのものの語彙を監査する


### 表示
† は辞書未統合の仮候補
国際的な指標略号は必要に応じて記号として保持する


## 1. 学習データと目的変数


Velka本文
Datvas sam=te datmen yel ir
Datmen ek be bi, modela=ji ba tan ir
†Kelmen ek, modela=pa ra kelvas ir
Datvas sam yel tan=ji tan-ke=n
Tan ek modela tarpil=ji
Tan bi modela pil=ji
Tan yel kelvas kel pil=ji
Ki tan sam=pa men vas-ke=n


### 監査点
†kelmen は目的変数・正解ラベル候補
train / validation / test は新語化せず、モデルを作る集合・調整に使う集合・最後に評価する集合として書ける


## 2. モデル学習


Velka本文
Modela datmen sam=fel jembor ra mak
Ki †modelatarpil ir
Modelamen sam munren-ke=n
Kasbal pit mak=ji modelamen tani mun-ke=n
Modela tarpil kel da, tani datvas=te pil-ke=n


### 監査点
†modelatarpil はモデル学習・訓練
既存 tarpil「研修・訓練」とmodelaの透明複合
人間の研修 tarpil と衝突せず、モデルに限定できる


## 3. 分類


Velka本文
Kelmen jembor bi ir
Modela piltan ek=ji jembor ek or bi jem
Ki jemsam ir
Modela jembor ek=pa †pekas 0.80 ra dori
†Jemkasrek 0.50 ir da, pekas rek kar tan jembor ek jem
Jemkasrek mun da, jemsam kelvas mun dori


### 監査点
分類自体は既存 jemsam で十分
†jemkasrek は分類閾値候補
pekas が高度統計から再登場


## 4. 回帰


Velka本文
Kelmen lik kas ir
Modela datmen sam=fel kelmen ra
Ki †datbenra ir
Nakas be ra kas tan kasben-ke=n
Kasbal lik-ke=n
Tani datvas=te datbenra pil-ke=n


### 監査点
†datbenra が高度統計側から再登場
統計回帰と機械学習回帰を同じ上位概念で扱える可能性が高い


## 5. 過学習と汎化


Velka本文
Modela tarpil datvas=te reni mag
Gera tani datvas=te gori ir
Ki tan=te modela tarpil dat=ji rek go ir
Modela=pa jembor mag pit mak be pilinrek ba da, tani datvas=te reni ne dori
Pilmun tani dat tan=ben mak-ke=n


### 監査点
過学習は専用語なしでも
「学習データにはよく適合するが、新しいデータには適合しない」
と明瞭に書ける
汎化も「別データで reni」で処理可能
現段階では新語化しない


## 6. 交差検証


Velka本文
Datvas sam yel jembor=ji tan-ke=n
Tan bi modelatarpil=ji pa be tan ek pil=ji pa
Mun tan be pilmun-ke=n
Kelvas sam kasren-ke=n
Ki pilmun data tan=pa modela kelvas ren ka pil


### 監査点
cross-validation は専用語を作らず、データ区分を交代させて反復検証する構文で表せる
高頻度化したら後で語彙化する


## 7. 評価指標


分類
Kelmen jembor ek ir tan=fel, modela ek jem tan=pa kassen vas
Kelmen jembor bi ir tan=fel, modela bi jem tan=pa kassen vas
Ki kassen sam recall / specificity 等の機能を持つ


Precision
Modela jembor ek jem tan=fel, kelmen ek ir tan=pa kassen


Recall
Kelmen ek ir tan=fel, modela ek jem tan=pa kassen


F1
Precision be Recall samben lik-ke kas
F1 men sami pa dori


AUROC
Jemkasrek tani mun be, kelmen ek ir tan=fel modela ek jem kassen be kelmen bi ir tan=fel modela ek jem kassen kasben tan vas
AUROC men sami pa dori


### 監査点
precision / recall / F1 / AUROC は定義をVelka語で説明できる
専門的な略号をそのまま用いても文法体系を壊さない
基礎辞書へ個別見出しを大量追加しない


## 8. 校正


Velka本文
Modela pekas ra
Pekas 0.70 tan sam=te irpan ne kassen 0.70 ir da, kasmunren reni
Ra pekas be irpan ne kassen kasben-ke=n
Kasmunren pit da, ra pekas munren balir


### 監査点
kasmunren はv2.0既存
pekas が確率予測にも自然に使える


## 9. 特徴量重要度


Velka本文
Datmen tani fel da, modela kelvas ke kas=te mun da ka pil
Kelvas mag mun da, u datmen=pa modela=ji bal mag
Ki datmen=pa jemkas tan vas dori
Gera rabal ka go di


### 監査点
feature importance は「その変数を除いたとき結果がどれだけ変わるか」など方法依存なので一語化しない
重要度と因果効果を区別する


## 10. 横断所見


高度統計から再登場
pekas
datbenra


機械学習固有候補
kelmen
modelatarpil
jemkasrek


既存語で十分
modela
datmen
datjem
jemsam
kasbal
kasren
kasmunren
pilren
pilinrek


新語不要寄り
train / validation / test
過学習
汎化
交差検証
precision
recall
F1
AUROC
特徴量重要度


## 11. データ分布の変化


Velka本文
Modelatarpil datvas=pa †datpan ek ir
Sen datvas=pa †datpan tani ir=na
Datpan mun raka modela kelvas gori ne dori
Sen datpan=te modela mun pil balir
Kasmunren be pilren mun jem balir


### 監査点
†datpan が機械学習でも再登場
「distribution shift」は専用語を作らず、学習時と新データの datpan が異なると記述できる