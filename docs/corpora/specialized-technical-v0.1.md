<!-- source: Google Drive 1n1VcgvdNzAmsYRZ0cuVko8oCjWsvthSuVcMemkQOjV0 -->
# Velka専門技術文コーパス v0.1


### 位置づけ
基礎辞書 v2.1 と
数理統計専門語彙 v0.1
因果推論専門語彙 v0.1
機械学習専門語彙 v0.1
を同時に運用する実地コーパス


専門見出しは基礎語と同じ文法に入る
国際記号はそのまま保持し、意味をVelka語で説明する


## 1. 数理統計技術ノート


題
Modelamen ra be kasbal
モデルパラメータ推定と不確実性


### 本文
Modela ek=te modelamen β ir
Datvas=fel modelamenkas 0.72 ra-ke=r
Rakasbal 0.10 ir=r
Kasbalrek 0.52=fel 0.92=ji ir=r


Raha zero β=0 ir
Rahakas 0.03 ir=na
Gera rahakas 0.03 raka raha zero fali ka go di
Modelamenkas mag-ne ir ka jem=r
Kasbalrek be datpan tan sami jem balir


Datpan sam ren go=na
Datkor be kasren tani ir=na
Datpankas mag ir=na
Datpekas raka modelamen tani kasben-ke=r


### 用語確認
modelamen
modelamenkas
rakasbal
rahakas
datpankas
datpekas
はL2専門語
β, p, SE, CIはL3記号


## 2. メタ解析技術ノート


題
Munratarvas sam=pa datbenjem


### 本文
Munratarvas tan tam=fel modelamenkas tan lu-ke=l
Tan sam=pa rakasbal be kasbalrek tani ir=lu
Datbenjem raka tan samben-ke=n
Samben modelamenkas 0.41 ir=r
Kelgor mag ir=r
I² 68% ir=r


Kelgor mag raka modela ek sam=ji reni go dori
Munratarvas sam=pa piltan be pilin tani ir=lu
Ki tani tan rabal raka kelgor ne dori=r


### 用語確認
datbenjem は統合分析
kelgor は統計的異質性
I² はL3記号


## 3. 因果図ノート


題
A, M, Y sam=pa rabalvas


### 本文
Rabalvas=te A=fel M=ji rabalpan ir
M=fel Y=ji rabalpan ir
M rabalpanmen ir


C=fel A=ji rabalpan ir
C=fel Y=ji rabalpan ir
C datbenrabal ir


Z=fel A=ji rabalpan ir
Z rabaltam ir dori
Gera Z=fel Y=ji direct rabalpan go ir balir


Rabalbenmen ek=ji A be U rabalpan ji da
Ki men rek go dori
Rabalbenmen rek da jemwe ne dori


### 用語確認
rabalpanmen と datbenrabal を分離
rabalbenmen を交絡因子と同一視しない


## 4. 潜在アウトカムと介入


題
Haikelvas be rabalmak


### 本文
An ek=pa haikelvas Y(1) be Y(0) ir
Gera ek ora=te tan bi direct na go dori


Rabalmak A=1 da, Y(1) ir
Rabalmak A=0 da, Y(0) ir
ATE sam=pa kasren kasben ir


Rabalren ir da, tani jempatan sam kasben dori
Rabalgur ir da, randapekas zero go ir
Rabaltar ir da, ATE datvas=fel ra dori


### 用語確認
Y(1), Y(0), ATEはL3記号
haikelvas は潜在アウトカム
rabalren / rabalgur / rabaltar は識別条件


## 5. 機械学習分類ノート


題
Modelatarpil be jemsam


### 本文
Datvas ek modelatarpiltan ir
Datvas bi modelapiltan ir
Kelmen jembor bi ir


Modelajembor gradient boosting ir
Modelamekalin sam munir jempa-ke=n
Modelatarpil mak-ke=n
Modelamunren raka modelakasbal pit mak-ke=n


Modelapekas 0.72 ir
Jemkasrek 0.50 ir
Modela jembor ek jem-ke=n


Jemdattan vas-ke=n
Precision 0.81 ir
Recall 0.74 ir
F1 0.77 ir
AUROC 0.86 ir


### 用語確認
precision / recall / F1 / AUROCはL3として保持
jemdattan により定義計算を説明可能


## 6. 正則化・アンサンブル・分布シフト


### 本文
Modela ek tarpil datvas=te reni mag
Gera sen datvas=te reni pit
Ki datpanmun ir


Modelarek ba-ke=n
Modelamekalin munren-ke=n
Modela mun pil-ke=n


Modelasam yel modela=fel mak-ke=n
Modelasam=pa kelvas ek modela=kas reni mag=r
Gera kasmunren mun pil balir


### 用語確認
datpanmun はdistribution shift
modelarek はregularization
modelasam はensemble


## 7. 横断比較


基礎辞書L0
modela
pekas
datpan
datkor
jempakasbal
datbenra
datbenrabal
kasbalrek
kasmunren


L2 数理統計
rahakas
datbenjem
kelgor
rakasbal
modelamen
modelamenkas
など


L2 因果推論
rabalvas
rabalpan
rabalpanmen
rabalbenmen
rabaltam
rabalmak
haikelvas
など


L2 機械学習
kelmen
modelatarpil
modelamekalin
modelakasbal
modelamunren
jemkasrek
jemdattan
modelarek
modelasam
datpanmun
など


## 8. 実地所見


専門語彙を別層にしても
SOV
証拠性
確度
条件 da
理由 raka
比較 kasben
否定 go
の基礎文法は変える必要がない


専門性は主に名詞・複合語・記号へ追加される


この構造なら
基礎辞書を覚えれば一般文を読め
必要な専門分野だけL2語彙を追加学習する
という運用が可能


## 9. 標本分布・分位・適合度


### 本文
Jempatan sam mun jemba be modelamenkas lik-ke=n
Modelamenkas sam=pa jempadatpan ir
Jempadatpan=pa datrek 0.025 be datrek 0.975 tan kas-ke=n
Ki rek sam kasbalrek=ben kasben dori


Pekaspan modela=fel datpekas vas-ke=n
Modelamen tani=te datpekas tani mun=na
Datpekas mag modelamen jempa dori
Gera modelaren be prediction reni sami go


### 用語確認
jempadatpan
datrek
pekaspan
datpekas
modelaren
を実文章で使用できることを確認


## 10. 調整集合・傾向スコア


### 本文
Rabalvas=te datbenrabal sam na-ke=n
Rabalrek sam jempa-ke=n
Rabalrek=pa datmen sam=fel randapekas ra-ke=n
Randapekas sami sam=te A=1 be A=0 tan kasben-ke=n
Rabalgur go ir sam fel-ke=n


Rabalrek raka datjem mun-ke=n
A be Y=pa datben mun ra-ke=n
Gera rabalbenmen rabalrek=bor te go balir


### 用語確認
rabalrek は調整集合
randapekas は傾向スコア
rabalbenmen を調整集合へ機械的に入れない


## 11. 専門見出し実使用監査


数理統計12見出し
すべて本コーパスまたは直前コーパスで実使用可能


因果推論12見出し
すべて本コーパスで実使用可能


機械学習12見出し
すべて本コーパスで実使用可能


専門辞書間で modelamen が共有されるため
登録数36
ユニーク専門見出し35


基礎辞書は913語のまま