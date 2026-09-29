<!-- source: Google Drive 1y2IE3GQYWjaGDBUtsFsAUerPyIYbHg003GssXmqUO-0 -->
# 機械学習専門語彙 v0.1


### 位置づけ
L2 機械学習専門見出し
基礎語 modela / datmen / datjem / datpan / pekas / datbenra / kasmunren / pilren を利用しつつ、モデル構築で反復する狭い概念のみ専門語化する


## 1. 専門見出し


kelmen [N-V]
目的変数・正解ラベル
モデルが推定・分類しようとする対象
〈N kel+men〉
数値予測ではtarget variable
分類ではtrue label
基礎辞書へはまだ昇格させない


modelatarpil [N-V/V]
モデル学習・訓練
データを用いてmodelaの内部値・構造を調整すること
〈N modela+tarpil〉


modelamen [N-V]
モデルパラメータ
学習によって推定・更新されるモデル内部の値
〈N modela+men〉
数理統計専門語彙と共通専門見出し


modelamekalin [N-V]
ハイパーパラメータ・モデル設定
学習前または外側の探索で定める設定値
〈N modela+mekalin〉
例
深さ、学習率、正則化強度


modelakasbal [N-V]
損失関数・loss
予測と目的値のずれを学習時に最小化するための量
〈N modela+kasbal〉
### 混同禁止
評価指標一般とは限らない


modelamunren [N-V/V]
最適化
modelakasbal 等を小さくする方向へmodelamenを反復調整すること
〈N modela+mun+ren〉


jemkasrek [N-V]
分類閾値
予測確率等をクラス判定へ変換する境界
〈N jem+kas+rek〉


jemdattan [N-III]
混同行列
正解クラスと予測クラスの組合せを数えた表
〈N jem+dattan〉
### 用途
precision / recall / specificity 等の計算


modelarek [N-V]
正則化
モデルの複雑さ・パラメータの大きさなどへ制約を加え、過学習を抑える方法
〈N modela+rek〉


modelajembor [N-V]
モデル族・アーキテクチャ
同じ構造原理を共有するモデルの種類
〈N modela+jembor〉
例
tree / neural network / linear model


modelasam [N-V]
アンサンブル
複数modelaをまとめて一つの予測に用いる構造
〈N modela+sam〉


datpanmun [N-V]
分布シフト
学習時と利用時でdatpanが変化すること
〈N datpan+mun〉
### 混同禁止
単なる個々の値の変化ではない


## 2. 生産的複合


modelatarpiltan
学習用データ区分


modelapiltan
検証・評価用データ区分


modelapekas
予測確率


datmenjempa
特徴量選択


modelakelvas
モデル出力


modelapilmun
交差検証・反復検証の透明複合候補
現時点では固定見出しにしない


## 3. 国際記号・名称


F1
AUROC
ROC
AUC
RMSE
MAE
R²


アルゴリズム名
random forest
gradient boosting
SVM
neural network
transformer
などはL3の固有技術名として保持できる


## 4. 指標の定義方針


precision
modela が陽性としたもののうち正解陽性の割合


recall
正解陽性のうちmodela が陽性とした割合


specificity
正解陰性のうちmodela が陰性とした割合


F1
precision と recall を統合した指標
F1 を国際記号として保持


AUROC
jemkasrek を動かしたときの真陽性率と偽陽性率の関係を要約した指標
AUROCを国際記号として保持


## 5. 使用例


Modelatarpil datvas ek=te mak-ke=n
Modelamekalin sam jempa-ke=n
Modelamunren raka modelakasbal pit mak-ke=n


Kelmen jembor bi ir
Modelapekas 0.72 ir
Jemkasrek 0.50 ir
Modela jembor ek jem-ke=n


Tani datvas=pa datpan mun=na
Ki datpanmun ir
Modela mun pil balir


## 6. v0.1時点の専門見出し数


12見出し
基礎辞書913語には加算しない