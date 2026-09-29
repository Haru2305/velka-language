<!-- source: Google Drive 1mzSTid0yz_efDzQi_r0YOR7w56kQl-uUN4asAi3K9ok -->
# Velka疫学・因果推論コーパス v0.1


### 位置づけ
現代語基礎辞書 v2.0（907語）を用い、疾病頻度・リスク比較・交絡・バイアス・因果推論を負荷試験する
以下はすべてVelka語開発用の架空データ


### 表示
† は辞書未統合の仮候補
疾病名や治療内容ではなく、研究方法の語彙を監査する


## 1. 有病と発症


Velka本文
Vel ek=te an sam 1000 ir
Kisol sanmar margoran 80 ir
Ki †margorirkassen 0.08 ir=na
Mon ek=bor sen margorji 30 ir
Ki †margorjikassen 0.03 ir=na


### 監査点
†margorirkassen は有病割合候補
†margorjikassen は発症割合候補
透明複合なので、辞書見出しではなく専門的な生産的複合として扱える可能性も高い


## 2. コホートとリスク


Velka本文
Tan ek=te rabal A lu-ke tan ir
Tan bi=te rabal A go lu-ke tan ir
Sol har mun, margorji tan tan vas-ke=n
Tan ek=pa †pekas 0.12 ir=na
Tan bi=pa †pekas 0.06 ir=na
Tan ek=pa pekas tan bi=kas bi kas ir
Ki †marrekkassen bi ir=r


### 監査点
曝露は専用語を作らず「要因Aを受けた／受けていない」で表現可能
†marrekkassen はリスク比候補
ただし比そのものは kassen で表現可能なので見出し語化は保留寄り


## 3. 症例対照とオッズ


Velka本文
Margorvas ir tan be margorvas go ir tan jemba-ke=n
Munir rabal A lu-ke da ka marvas=fel lu-ke=l
Margor tan=te A lu tan mag=lu
Go margor tan=te A lu tan pit=lu
A lu / go A lu kassen tan kasben-ke=n
Ki kassen tani vas dori


### 監査点
オッズ比は新語化せず、病気あり群となし群で「曝露あり／なし」の比を比較する構文で書ける
国際的な記号 OR を専門記号として併用してもよい


## 4. 交絡


Velka本文
A be margorji datben ir=r
Datmen C, A=ben datben ir=na
C, margorji=ben datben ir=na
Ki C †datbenrabal ir dori
C=pa rek tani sam=te datjem mun-ke=n
A be margorji datben pit-ne=na
Rabal jem=pa certainty fel-ne=r


### 監査点
†datbenrabal が高度統計側から再登場
疫学では中核語彙として強く必要


## 5. 効果修飾・交互作用


Velka本文
An sam tan bi ir
Tan ek=te A be margorji datben mag=r
Tan bi=te datben pit=r
A sami ir gera datben tani ir
Ki datben=pa kas sam=pa jembor raka mun
Rabal ek sam=ji sami kelvas ba ka go jem


### 監査点
「効果修飾」は専用語なしでも「集団によって関連の大きさが異なる」と書ける
交互作用を一語化する前に、統計モデル側での需要を確認する


## 6. 選択・情報バイアス


Velka本文
Piltan sam=fel tani an=rek piltar=bor ara-ke=n
Ki jemparek raka jempatan tan-ke=n
Jemparek kelvas=ben datben ir da, †jemwe ne dori
Munir marvas irpan=kas tani ir da, kerfal raka †jemwe ne dori
†Jemwe datben tan mag-ne mak dori


### 監査点
jemwe はv2.0既存
選択・想起・測定などの種類を複合で細分化できるため、個別の「○○バイアス」を基礎辞書へ大量追加しない


## 7. 因果効果


Velka本文
A lu tan=pa kelvas na-ke=n
Gera tani tan A go lu da, tewan=pa kelvas na go dori
Ki hai tan raka, rabal be kelvas ben na go dori
Randa ir da, tani tan sam=pa datben rabal=ji ji dori
Randa go ir da, datbenrabal tan rek balir


### 監査点
反実仮想の専用文法は作らず、「同じ対象が別条件なら」という未観察条件を OPEN と条件 da で表現する
因果効果は rabal + kelvas で分析的に扱える


## 8. 標本誤差と精度


Velka本文
Jempatan pit da, †jempakasbal mag=r
Jempatan mag da, †jempakasbal pit-ne=r
Marrekkassen=pa †kasbalrek mag ir da, jem certainty pit
Kasbalrek pit da, ra reni mag


### 監査点
†jempakasbal が高度統計側から再登場
kasbalrek はv2.0既存
「precision」は専用語を置かず、不確実性区間の狭さで表現する


## 9. 横断所見


高度統計から再登場
pekas
datbenrabal
jempakasbal


疫学固有候補
margorirkassen
margorjikassen
marrekkassen


既存語で十分
jemwe
randa
kasbalrek
jempatan
jemparek
margorji
margoran
marvas


新語不要寄り
曝露
オッズ比
効果修飾
因果効果
精度


## 10. 年齢・測定値の分布


Velka本文
Margoran sam=pa yar nakas sam †datpan ir
†Datkor 42 yar ir=na
Datpan tani sam=te mag be pit tan tani ir=na
Tan ek be tan bi=pa datpan sami go
Datmen tani go rek da, ki kassen sam raka jem kel go dori


### 監査点
†datpan と †datkor が疫学記述でも再登場
平均だけでなく中央値・分布が必要になるため、統計専用に閉じない可能性が高い