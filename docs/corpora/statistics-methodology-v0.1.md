<!-- source: Google Drive 1LsoxgiN5RmkWqX-ecmqI41ao-k1fMjFGBKfgleDK_7Y -->
# Velka統計・方法論コーパス v0.1


### 位置づけ
現代語基礎辞書 v1.9（897語）を起点に、科学論文で保留した統計・方法論概念を実地試験する
題材は主に「日照時間と幼植物の高さ」という既存科学コーパスと同じ架空データを用い、分野語彙ではなく統計語彙そのものを負荷試験する
以下の数値・研究はすべてVelka語開発用の架空例


### 表示
† は辞書未統合の仮候補
既存語・自由構文で自然に表せる場合は新語化しない


## 1. 記述統計


### 目的
Datmen sam=pa jembor be kas tan vas
データの分布・中心・ばらつきを記述する


Velka本文
Datmen ek halkas ir
Nakas sam lik be tan-ke=n
Kasren 12.4 ir=na
†Datkor 12.1 ir=na
Nakas sam kasren=rek go samben
†Datpan tani ir=na
†Datpankas 2.3 ir=na
Nakas pit tan hal=te, tani mag tan fel=te ir=na


### 監査点
平均 kasren は既存語で十分
中央値は「中央の観測値」と分析的に書けるが高頻度なので †datkor を試す
分布は †datpan、ばらつきは †datpankas を仮置き


## 2. 標本と母集団・標本誤差


### 目的
Jempatan=fel sam mag=pa kas tan ra
標本からより大きな集団を推定する


Velka本文
†Jempatan piltan sam=fel jemba-lu tan ir
Ki jempatan=pa kasren nakas=na
Sam mag=pa kasren direct go na
Jempatan tani jemba da, kasren tani mun dori
Ki tani †jempakasbal ir
Jempatan mag da, †jempakasbal pit-ne=r
Gera jempatan mag=rek rabal sam fal go


### 監査点
標本 jempatan、研究単位 piltan はv1.9で既存
標本誤差は既存 kasbal をそのまま使うと測定誤差と混同するため †jempakasbal を試す


## 3. 区間推定


### 目的
Ek kas=rek go, kasbal=pa rek tan vas
一点だけでなく不確実性の範囲を示す


Velka本文
Kasren 12.4 ir=na
†Kasbalrek 11.9=fel 12.9=ji ir=r
Ki rek, jempatan=fel sam mag=pa kas ra tan jem
†Kasbalrek pit da, ra tani reni mag
Gera †kasbalrek=bor ir ka, fact ki rek=bor ir ka go di
Tani jempatan=te rek mun dori


### 監査点
†kasbalrek は科学論文監査から持ち越した候補
「信頼区間」を確率そのものと誤解しないよう、意味はまず「推定不確実性を表す区間」として固定する


## 4. 仮説検定


### 目的
Raha be nakas tan kas be jem
仮説と観測結果のずれを評価する


Velka本文
Raha zero ir
Tan ek be tan bi=pa kasren sami ka raha
Nakas sam=te tan tani ir=na
†Rahakas raka, ki tani raha=kas mag da ka jem
†Rahakas pit=na
Gera †rahakas pit ir raka raha zero fali ka go di
Kelvas=pa kas, jempatan kas, pilin tani samben jem balir


### 監査点
p値に相当する量をそのまま「仮説が正しい確率」としない
仮候補 †rahakas は「帰無仮説のもとで観測結果以上のずれが得られる程度を示す統計量」としてのみ試す
「統計的有意」は専用語をまだ作らず、基準との比較で表す


## 5. 回帰・モデル


### 目的
Datmen tani sam=pa datben tan ra be vas
複数の変数と結果の関係を推定する


Velka本文
Datmen ek solbel ora ir
Datmen bi halkas ir
†Modela ek=te datben tan te-ke=n
†Datbenra raka solbel ora=pa tan mun be halkas=pa tan mun samben jem-ke=n
Solbel ora ek mag da, halkas kas 0.8 mag-ne=r
Gera ki kas jempatan=pa datpan be pilin=ji bal
†Modela tani=te kelvas tani mun dori


### 監査点
「モデル」は高度専門語であり、無理な固有語化より学術借用 †modela が自然かを試す
「回帰」は †datbenra として「データ関連から推定する」と透明に表す候補を試す
係数・切片は現段階では専用語を作らず、変数一単位変化あたりの結果変化として表現する


## 6. 交絡と調整


### 目的
Datben be rabal tan tani mak
関連と因果を混同しない


Velka本文
Solbel ora be halkas datben ir=r
Gera wa kas, solbel ora=ben be halkas=ben datben ir=na
Ki wa kas †datbenrabal ir dori
Wa kas sami rek be, solbel ora be halkas datben mun jem-ke=n
Mun jem kelvas mun da, munir datben=kas pit-ne=na
Ki tan raka rabal ka jem=pa certainty fel-ne=r


### 監査点
†datbenrabal は「観測された関連の一部または全部を生じうる第三要因」の候補
「調整」は新語化せず「第三変数を一定範囲に置いて再分析する」という構文で処理できるか確認する
調整前後で推定が変わることを明示すれば、専用動詞は不要な可能性が高い


## 7. 無作為化・盲検


### 目的
Jempatan sam=ji pilin tani ba=pa jemwe pit mak
割付や測定に生じる系統的な偏りを減らす


Velka本文
Piltan sam tan bi=ji ba balir
Ba=pa pilin piltaran=pa jem raka go mun balir
†Randa raka piltan tan bi=ji ba-ke=n
Tan men pil mak-an=fel rek-ke=n
Kas mak-an tan men go lu-ke=n
Ki raka †jemwe pit mak ka jem=r


### 監査点
「無作為化」は一般語から長く説明すると重いため、近代学術借用候補 †randa を試す
「盲検」は新語化せず「群名を測定者へ知らせない」で書けるか確認する
†jemwe は科学論文監査からのバイアス候補
ここでは「判断・選択・測定を一定方向へずらす系統的要因」として意味を狭めて再試験する


## 8. 欠測と感度分析


### 目的
Datfal ir da kelvas ke kas=te ren dori ka pil
欠測が結論へ与える影響を確認する


Velka本文
Datmen bi=te datfal ir=na
Datfal tan piltan sam=te sami go
Datfal mag tan=fel datjem ek mak-ke=n
Datfal fel ka jem be datjem bi mak-ke=n
Datjem ek be bi=pa kelvas kasben-ke=n
Kelvas sami da, datfal=pa bal pit ka jem=r
Kelvas tani da, datfal rabal tani pil balir


### 監査点
欠測 datfal はv1.9で既存
「感度分析」は新語を作らず、前提や欠測処理を変えて同じ分析を繰り返し比較する構文で十分か試す


## 9. 校正・検証


### 目的
Ra kas be nakas kas tan kasben
予測値と観測値の一致を評価する


Velka本文
†Modela raka piltan sam=pa kelvas kas ra-ke=n
Tani piltan sam=te nakas kas-ke=n
Ra kas be nakas kas tan sam=te kasben-ke=n
†Kasmunren mag da, ra kas be nakas kas reni ir
†Kasmunren pit tan=te ra kas mag gera nakas pit ir=na
Tani jempatan=te †pilren pil-ke=n


### 監査点
†kasmunren は「校正」候補として方法論・予測モデル双方で再登場
pilren はv1.9既存の再現性
「内部検証・外部検証」は新語化せず、同じ標本か別標本かを明示する


## 10. メタ解析・異質性・バイアス


### 目的
Munratarvas sam=pa kelvas tan samben jem
複数研究の結果を統合して評価する


Velka本文
Munratarvas tan tam jemba-lu=na
Tan sam=pa datben be kasbalrek lu-ke=l
†Datbenjem raka kelvas sam samben-ke=n
Samben kas ek ir=r
Gera tan sam=pa kelvas sami go=lu
Ki tani †Kelgor ir
Pilin, jempatan, datmen tani raka kelgor ne dori=r
Vasdar=te kelvas mag ratarvas=rek mag lu dori
Ki tan †jemwe ek ir dori
†Datbenjem mun, kelgor be jemwe tan jem balir


### 監査点
†datbenjem は「複数研究の推定値を統合する分析」として意味が安定
†kelgor は研究間異質性候補
†jemwe は出版・選択・測定などを含む上位概念「系統的偏り」として使えるか確認


## 11. v0.1横断所見


強く反復
kasbalrek
modela
datbenra
datbenrabal
randa
jemwe
kasmunren
datbenjem
kelgor


分析的表現で足りそう
調整
盲検
感度分析
内部検証・外部検証
統計的有意


既存語で十分
kasren
kasbal
jempatan
datmen
datjem
datben
datfal
pilren


医学論文側での再監査結果
randa
jemwe
kasbalrek
modela
に加えて kasmunren も再登場した
この5語を科学共通語として正式統合候補とする