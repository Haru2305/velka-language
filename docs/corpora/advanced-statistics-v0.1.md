<!-- source: Google Drive 1vF8WbBENevhceaNPoPhIAyx04ZMvE2Ui7oavrI30Nh0 -->
# Velka高度統計コーパス v0.1


### 位置づけ
現代語基礎辞書 v2.0（907語）を起点に、高度統計で必要になる概念を負荷試験する
記述統計・確率・推定・回帰・因果・メタ解析を通し、統計専用語と科学共通語を分ける
以下の数値・研究はすべてVelka語開発用の架空例


### 表示
† は辞書未統合の仮候補
式・記号で済む概念は無理に語彙化しない


## 1. 確率


### 目的
出来事が生じうる程度を数で表す


Velka本文
Irpan ek ne=pa †pekas 0.30 ir
Irpan bi ne=pa †pekas 0.70 ir
†Pekas zero da, irpan go ne ka jem
†Pekas ek da, irpan di ne ka jem
Gera piltar dat=fel †pekas ra da, ki kas certainty sam go


### 監査点
†pekas は pe「可能性」＋kas「測る」
確率を単なる主観的可能性ではなく、0から1までの測定可能な量として扱う


## 2. 分布・中央値・分位


Velka本文
Datmen ek=pa nakas sam tani rek=te tan-ke=n
Ki †datpan ir
Kasren 10.4 ir=na
†Datkor 9.8 ir=na
Nakas sam=pa hal rek be fel rek tani vas-ke=n
Ki †datrek tani ir
Datpan ek=te hal tan mag, tani datpan=te kor tan mag


### 監査点
†datpan 分布
†datkor 中央値
†datrek 分位境界
平均 kasren と別に必要かを確認する


## 3. 標本・推定


Velka本文
Jempatan sam=fel sam mag=pa kas ra-ke=r
Jempatan tani da, ra kelvas tani mun dori
Ki tani †jempakasbal ir
Jempatan mag da, †jempakasbal pit-ne=r
Kasbalrek raka ra kelvas=pa uncertainty rek vas-ke=n


### 監査点
†jempakasbal は標本誤差
既存 kasbal は測定誤差なので区別価値がある


## 4. 仮説検定


Velka本文
Raha zero ir
Nakas sam raha zero=kas tani ir=na
Ki tani=pa †rahakas 0.04 ir=na
†Rahakas pit raka raha zero fali ka go di
Jemparek munir 0.05 ir da, ki kelvas jemparek=fel pit ir
Gera kelvas=pa kas mag ka tani vas balir


### 監査点
†rahakas はp値候補
p値を「帰無仮説が正しい確率」と定義しない
語彙化より記号pを併用する可能性も残す


## 5. 回帰


Velka本文
Modela ek datmen yel samben-ke=n
Kelmen ek ir
Datmen bi be yel=pa kelmen=ji datben ra-ke=r
Ki †datbenra ir
Modelamen sam=pa kas tani vas-ke=n
Datmen bi ek mag da, kelmen 0.7 mag-ne=r
Gera modela pilinrek ir


### 監査点
†datbenra を回帰候補として再試験
新候補 †kelmen は目的変数・予測対象の一般名
modelamen は「モデル内で名づけられた項」と分析的に使えるため、現段階では見出し語化しない


## 6. 交絡・因果推論


Velka本文
Datmen A be kelmen datben ir=r
Datmen C, A=ben datben ir=na be kelmen=ben datben ir=na
Ki C †datbenrabal ir dori
C sami rek be datjem mun-ke=n
A be kelmen=pa datben pit-ne=na
Rabal jem=pa certainty fel-ne=r


### 監査点
†datbenrabal は交絡候補
関連 datben と原因 rabal を一語に混ぜない
調整は自由構文で処理する


## 7. メタ解析


Velka本文
Munratarvas tan tam=pa kelvas lu-ke=l
Tan sam=pa modela kelvas be kasbalrek samben-ke=n
Ki †datbenjem ir
Samben kelvas ek ne-ke=r
Gera kelvas sam sami go=lu
Ki †kelgor ir=r
Kelgor mag da, samben kelvas=pa tar pit-ne=r


### 監査点
†datbenjem はメタ解析候補
†kelgor は研究間異質性候補
単なる「研究結果の不一致」と統計的異質性を区別できるかを見る


## 8. ベイズ更新


Velka本文
Munir jem=pa †pekas 0.20 ir
Sen jemfel lu da, †pekas mun-ke=r
Munir pekas be sen jemfel samben jem-ke=r
Ki pilin=te raha ek di go
Jemfel mun da pekas mun dori


### 監査点
「事前・事後」を新語化せず munir / sen と pekas の組合せで書ける
ベイズ専用語彙は現段階で不要


## 9. 横断所見


強く必要
pekas
datpan
datkor
jempakasbal
datbenra
datbenrabal
datbenjem
kelgor


限定的
datrek
rahakas
kelmen


既存語で十分
kasren
kasbal
kasbalrek
modela
modelaren? は不要、reni で表現
datmen
datjem
datben
pilren