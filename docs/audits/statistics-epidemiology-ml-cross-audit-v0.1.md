<!-- source: Google Drive 1b1uVNRtielNbMmGD98HhPhxeGD9frvi7CNFIt2kulyI -->
# 統計・疫学・機械学習 横断監査 v0.1


### 位置づけ
現代語基礎辞書 v2.0（907語）を基準に
Velka高度統計コーパス v0.1
Velka疫学・因果推論コーパス v0.1
Velka機械学習コーパス v0.1
を横断監査する


### 目的
専門領域ごとの用語を大量に基礎辞書へ入れず、複数領域で独立に必要となった概念だけを正式統合候補とする


## 1. 仮候補の出現


3領域すべて
pekas
高度統計 8
疫学 2
機械学習 1
合計 11


datpan
高度統計 2
疫学 2
機械学習 3
合計 7


高度統計＋疫学
jempakasbal
3 + 3 = 6


datbenrabal
2 + 2 = 4


datkor
2 + 2 = 4


高度統計＋機械学習
datbenra
2 + 2 = 4


kelmen
1 + 2 = 3


## 2. 正式統合候補 6語


pekas [N-V]
確率；出来事が生じる可能性を0から1などの尺度で表した量
〈N pe+kas〉
pe は可能性、kas は測る
単なる主観的「ありそう」と数理的確率を文脈で区別できる


datpan [N-V]
分布；データ値が範囲内でどのように広がっているかという構造
〈N dat+pan〉
統計記述、疫学集団記述、機械学習の分布変化で共通して必要


datkor [N-V]
中央値；順序づけたデータの中央に位置する値
〈N dat+kor〉
kor「中心」の意味拡張
平均 kasren と独立に必要


jempakasbal [N-V]
標本誤差；標本を選んだことにより推定値に生じる変動・ずれ
〈N jempa+kasbal〉
測定誤差 kasbal と分離する
単なる選択バイアス jemwe とは異なり、確率的標本変動も含む


datbenra [N-V/V]
回帰；変数間の関係から結果変数を推定・記述する統計的方法
〈N dat+ben+ra〉
統計学と機械学習の双方で同じ上位概念として使用可能
線形・ロジスティック等の下位分類は専門複合または借用で処理


datbenrabal [N-V]
交絡；ある要因が複数の変数と関連し、観測された関連の因果解釈を歪めうる関係・要因
〈N dat+ben+rabal〉
関連 datben と原因 rabal を区別するために必要
疫学だけでなく観察データ一般の因果推論に使用可能


## 3. 保留候補


kelmen
統計では目的変数
機械学習では正解ラベル・予測対象
意味が広がり始めている
「アウトカム変数」「target」「class label」を一語に潰すか未確定
現時点では datmen + kelvas / jembor の分析的表現を優先


datrek
分位境界
統計専用性が高い
quantile / percentile の体系を作る際に再監査


rahakas
p値候補
誤解の危険が大きい
専門記号 p と定義構文を優先し、基礎辞書へ入れない


datbenjem
メタ解析候補
科学論文・高度統計で必要だが利用領域が限定的
専門統計語彙層へ


kelgor
異質性候補
一般的不一致と統計的heterogeneityの境界がまだ不十分
専門統計語彙層へ


margorirkassen
有病割合候補
透明な生産的複合として作れるため、基礎辞書見出しにしない


margorjikassen
発症割合候補
同上


marrekkassen
リスク比候補
marrek + kassen の透明複合で十分


modelatarpil
モデル学習
modela + tarpil の透明複合
機械学習で高頻度でも語形成で毎回理解可能なため、現時点では辞書化不要


jemkasrek
分類閾値
機械学習・診断判定で再登場する可能性あり
次の分類・診断コーパスで再監査


## 4. 新語化しなかった重要概念


曝露
「要因を受ける／経験する」lu構文


オッズ比
曝露あり／なし等の比 kassen を明示して比較


効果修飾
集団ごとに datben の大きさが異なると記述


反実仮想
OPEN + 条件 da により未観察条件として表現


過学習
学習データでは reni、別データでは gori と分析的に記述


汎化
別データで reni かを確認


交差検証
データ区分を交代させて pilmun


precision / recall
分母・分子を明示した kassen


F1 / AUROC
国際的な技術記号を保持し、定義はVelka語で記述


feature importance
datmen を除いたときの kelvas 変化等、方法に応じて記述


## 5. v2.0既存語の機能確認


modela
統計・医学・機械学習で安定


randa
実験・因果推論で安定


jemwe
選択・測定・公表等のバイアス上位語として安定


kasbalrek
区間推定・疫学・医学で安定


kasmunren
計測・予測モデル校正で安定


datmen
変数／特徴量の上位概念として安定


datjem
分析の上位概念として安定


datben
相関・関連の上位概念として安定


pilren
再現性の上位概念として安定


## 6. 語彙階層


基礎科学語彙
pekas
datpan
datkor
jempakasbal
datbenra
datbenrabal


統計専門語彙
datrek
rahakas
datbenjem
kelgor


疫学専門の生産的複合
margorirkassen
margorjikassen
marrekkassen


機械学習専門の生産的複合
modelatarpil
jemkasrek
将来的な kelmen 系


## 7. 結論


3領域を横断した結果
6語は基礎辞書へ正式統合可能
その他は専門語彙層または生産的複合として保持する


これにより
統計学
疫学・因果推論
機械学習
の専門性を増しても、基礎辞書が専門用語で過剰に膨張することを避けられる


実施結果
pekas / datpan / datkor / jempakasbal / datbenra / datbenrabal の6語を現代語基礎辞書 v2.1へ正式統合した
基準辞書は907語 + 6語 = 913語となった