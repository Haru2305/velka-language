<!-- source: Google Drive 19ByFl_3hOA2e-Yi4zdsd9n3TOuyqoo1mOTgR0N3f0Es -->
# 因果推論専門語彙 v0.1


### 位置づけ
L2 因果推論専門見出し
観察データから原因を論じる際に必要な概念を、基礎語 datben / rabal / datbenrabal / randa / jemwe の上に構築する


## 1. 専門見出し


rabalvas [N-V]
因果図・因果グラフ
変数間の原因方向を図・記録として表した構造
〈N rabal+vas〉
### 記号対応
DAG をL3として保持してよい


rabalpan [N-V]
因果経路
ある要因から結果へ至る原因関係の連鎖
〈N rabal+pan〉


rabalpanmen [N-V]
媒介変数
原因から結果への rabalpan の途中に位置する変数
〈N rabalpan+men〉
### 混同禁止
交絡 datbenrabal


rabalbenmen [N-V]
コライダー
複数の原因経路が同一変数へ流入する接合点となる変数
〈N rabal+ben+men〉
### 混同禁止
交絡因子ではない


rabaltam [N-V]
操作変数・instrument
原因候補へ影響するが、結果へは主としてその原因候補を介して作用する変数
〈N rabal+tam〉
### 記号対応
IV
### 混同禁止
単なる予測変数ではない


rabalmak [N-V/V]
介入
ある変数を観察するだけでなく、外部から設定・変更すること
〈N rabal+mak〉
### 記号対応
do(A=a)


haikelvas [N-V]
潜在アウトカム
実際には観察されなかった条件下を含む、可能な結果
〈N hai+kelvas〉
### 記号対応
Y(1), Y(0)


rabalren [N-V/SV]
交換可能性
比較群間で、処置以外の原因構造が因果効果推定に必要な程度に対応している条件
〈N rabal+ren〉
### 混同禁止
単なる統計的一致ではない


rabalgur [N-V/SV]
positivity・正値性
対象となる共変量条件のもとで、比較する各処置を受ける可能性が0でない条件
〈N rabal+gur〉
### 混同禁止
一般的「許可」gurとは専門文脈で区別


rabaltar [N-V/V]
識別・identification
観察可能な分布と仮定から、目的とする因果量を一意に定められること
〈N rabal+tar〉


rabalrek [N-V]
調整集合
因果効果を推定するために条件づけ・調整する変数集合
〈N rabal+rek〉
### 混同禁止
すべての関連変数を入れればよいわけではない


randapekas [N-V]
傾向スコア
観察された共変量のもとで処置を受ける確率
〈N randa+pekas〉
### 記号対応
e(X)
### 用途
matching / weighting / adjustment


## 2. 基礎語との役割分担


datben
関連


rabal
原因


datbenrabal
交絡


randa
無作為化


jemwe
系統的バイアス


rabalmak
介入


haikelvas
潜在アウトカム


## 3. 国際記号


DAG
do(A=a)
ATE
ATT
CATE
IV
Y(1)
Y(0)
e(X)


記号はそのままL3として保持する


## 4. 使用例


Rabalvas=te A=fel M=ji rabalpan ir
M rabalpanmen ir
C A=ben be Y=ben datben ir
C datbenrabal ir dori


Rabalmak A=1 da, haikelvas Y(1) ir
Rabalmak A=0 da, haikelvas Y(0) ir
ATE tan=pa kasben ir


Randapekas pit go ir balir
Ki tan rabalgur ir


## 5. 混同防止


mediator と confounder を同一語で扱わない
collider を交絡因子として調整しない
prediction と causal effect を同一視しない
association datben と cause rabal を明示的に分離する


## 6. v0.1時点の専門見出し数


12見出し
基礎辞書913語には加算しない