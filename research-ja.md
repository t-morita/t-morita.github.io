---
layout: ja_page
ja_title: 研究内容
permalink: /research-ja/
---
現在のWeb コンテンツは，人間が理解することを目的として構築されているため，ソフトウェアによる理解は困難です．一方，次世代Web の候補の一つであるセマンティックWeb は，ソフトウェアが意味理解可能な辞書（オントロジー）に基づいて，Web コンテンツにソフトウェア可読なメタデータを付与することによって，ソフトウェアがWeb コンテンツを理解し，推論することを可能にしようという試みです．セマンティックWeb の実現により，知的な情報検索やアプリケーションを横断したデータ統合および再利用などが可能になることが期待されています．しかしながら，ソフトウェアがWeb コンテンツを理解するためのセマンティックWeb標準技術である，RDF，RDFS，OWLにより記述されるセマンティックWeb コンテンツの構築には，多大なコストを要しています．以上の背景より，セマンティックWebコンテンツの構築コストを低減するために，セマンティックWeb コンテンツ構築支援に関する研究にこれまで主に従事してきました．これまでに取り組んできた主な研究テーマとその概要は，以下のとおりです．

* [Integrating Smart Glasses with Question-Answering Module in Assistant Work Environment](#section-14)
* [Implementing Mobility Service with Japanese Linked Data](#section-13)
* [Identifying Behavior Objective from Traffic Behavior Log Data by Using Facility Ontology](#section-12)
* [Linked Data とルールベースの統合に基づく食事療法支援サービスの開発と評価](#section-11)
* [SCOR オントロジーに基づく生産管理プロセスモデリング支援ツールの実装](#section-10)
* [大規模Linked Open Dataのための日本語語彙の構築](#section-9)
* [Building up a class hierarchy with properties by refining and integrating Japanese Wikipedia Ontology and Japanese WordNet](#section-8)
* [WikiBOKを用いた社会情報学の知識体系構築実験](#section-7)
* [日本語Wikipediaからプロパティを備えたオントロジーの構築](#section-6)
* [Wikipediaを活用したセマンティックWebコンテンツの半自動構築およびWeb APIの実装](#section-5)
* [日本語Wikipediaからの大規模オントロジー学習](#section-4)
* [エンタープライズアプリケーションオントロジーに基づく業務アプリケーション開発支援](#section-3)
* [DODDLE-OWL: Interactive Domain Ontology Development with Open Source Software in Java](#section-2)
* [A Graphical RDF-based Meta-Model Management Tool](#section-1)

# <a id="section-14">Integrating Smart Glasses with Question-Answering Module in Assistant Work Environment</a>
## Abstract
Recently, smart glasses have been applied in field work, with which a worker goes well during work by contacting a support operator from a remote location. The worker, however, cannot go well if the support operator is not there. To solve the issues, the paper discusses how a work system should be developed by integrating smart glasses with a question-answering module. We design the work knowledge acquired from skilled people and manuals as a work flow, rule base, goal tree, domain ontologies and RDF data. Workers follow work process by referring to the work flow, referring to multimedia, and receiving answers from the question-answering module incorporated with a knowledge base for questions that are raised during the work. The authors conducted a demonstration experiment and found that workers could perform the work more autonomously by importing the system.

## Related paper
* Ryutaro Nambu, <u>Takeshi Morita</u>, Takahira Yamaguchi, "Integrating Smart Glasses with Question-Answering Module in Assistant Work Environment", The Review of Socionetwork Strategies, Vol. 11, Issue 1, pp. 1-16 (2017) [10.1007/s12626-017-0003-4](https://doi.org/10.1007/s12626-017-0003-4)

# <a id="section-13">Implementing Mobility Service with Japanese Linked Data</a>
## Abstract
This study aims at developing a web service with Japanese Linked Data and evaluating the service. Recently, Japanese government has set open data as a new strategy in information technology field and focuses on 'Linked Open Data (LOD)' as a means to publish. However, the number of dataset as Japanese Linked Data is small, and the effect by introducing Japanese Linked Data has not been shown yet. Therefore, we created Japanese Linked Data focused on geographical or positional data, and implemented a mobility service to reduce user's cognitive load. Moreover, we conducted verification experiment for using the service and compared with conventional services. As a result, the possibilities of Linked Data to respond to various queries easily and to apply for information services by crossing some domains were explored.

## Related paper
* <u>Takeshi Morita</u>, Chie Iijima, Wataru Okawara, Yoshitaro Enomoto, Takahira Yamaguchi, "Implementing Mobility Service with Japanese Linked Data", International Journal of Computational Intelligence Studies, Vol. 5, No. 3/4, pp.267-288 (2016) DOI: [10.1504/IJCISTUDIES.2016.083573](https://doi.org/10.1504/IJCISTUDIES.2016.083573)

# <a id="section-12">Identifying Behavior Objective from Traffic Behavior Log Data by Using Facility Ontology</a>
## Abstract
Traffic behaviour surveys by hand require both a lot of money and human resources. Recently, traffic behaviour surveys using information technology have been carried out. In this study, we propose a method to extract staying points from GPS-based positional data, to identify the types of staying facilities by using Google Places API, a facility ontology, the regularity which is analysed from trip chains about traffic behaviour and to determine the behaviour objectives based on the rules between the behaviour objectives and the types of staying facilities. This method could identify 67.9% behaviour objectives in the evaluation using GPS location data from the traffic behaviour survey in Nagasaki.

## Related paper
* Yu Sugawara, <u>Takeshi Morita</u>, Hidenao Abe, Shuichi Matsumoto and Takahira Yamaguchi，"Identifying Behavior Objective from Traffic Behavior Log Data by Using Facility Ontology", Special Issue on Data Mining and Service Science for Innovation, International Journal of Knowledge Engineering and Soft Data Paradigms, Vol. 5, No.2, pp.68-84 (2016) DOI: [10.1504/IJKESDP.2016.075975](http://dx.doi.org/10.1504/IJKESDP.2016.075975)

# Software
* [SmaphoProbe](https://github.com/smaphoprobe/SmaphoProbe)


# <a id="section-11">Linked Data とルールベースの統合に基づく食事療法支援サービスの開発と評価</a>
## 概要
本稿では，Linked Data の新しい利用法として，タスク入力データとLinked Dataを連携させ，データ変換結果を作業領域に蓄積させ，その作業領域にタスクを処理するためのRB(ルールベース)を適用して，タスク出力結果を得る，Linked Data と RB を統合する情報サービスを提案したうえで，Linked Dataを利用する優位性について考察する．

具体的には，飲食店におけるメニュー表画像から各メニューにおける栄養計算結果を出力可能な食事療法支援サービスの開発と評価を目的とする．メニューから栄養計算を行うためには，飲食店のメニューと類似するレシピ情報の取得，そのレシピから料理を作るために必要な材料とその分量の推定，分量表記のグラム表記への統一，各材料におけるエネルギー計算，各材料の食品分類の取得など，様々な処理が必要となり，入力データと出力データの情報粒度に乖離がある．本研究では，その乖離を埋めるためにメディエータを用意する．

本研究における新規性は，Linked Dataの新しい利用法として，Linked DataとRBの統合に基づいた情報サービスを提案している点にある．また，ケーススタディとして，Linked DataとRBの統合に基づく糖尿病患者のための食事療法支援サービスを実現した点が本研究における貢献である．Linked DataとRBを用いる利点としては，サービスの機能拡張が容易になること（機能拡張容易性）および類似タスクについてサービス追加が容易になること（タスク追加容易性）が挙げられる．本研究では，機能拡張容易性を実証するために，アレルギーLinked Dataとの連携を行った．また，タスク追加容易性を実証するために，高血圧患者のための食事療法支援サービスの実装コストを調べた．さらに，食事療法支援サービスを評価するために，既存の類似アプリケーションとの比較評価および食事療法を必要とするユーザによるネットアンケート調査を実施した．

## 関連論文
* 多川 勇介，田中 改，<u>森田 武史</u>，南 裕也，並河 大地，下村 道夫，山口 高平，"Linked Data とルールベースの統合に基づく食事療法支援サービスの開発と評価"，人工知能学会論文誌，Vol.31, No1 pp.16-28, (2016) DOI: [10.1527/tjsai.31-1_LOD-B](http://dx.doi.org/10.1527/tjsai.31-1_LOD-B)

# <a id="section-10">SCOR オントロジーに基づく生産管理プロセスモデリング支援ツールの実装</a>
## 概要
本研究では，参照モデルと現場のプロセスのモデル（AS-ISモデル）を比較し，相違点を特定する手法の提案およびそのツールの開発を目的とする．これにより，現場の担当者に，AS-ISモデルの良い部分と悪い部分の両面に気付きを与えて，現状をあらためて深く理解することを支援する．具体的な参照モデルとしては，サプライチェーン管理を対象とするSupply-chain operations reference-model （SCORモデル）を採用する．本研究の目的を達成するために解決すべき問題が3つある．問題(1)は，AS-ISモデルと参照モデルを計算機可読な形式で作成することである．問題(2)は，AS-ISモデルと参照モデルの抽象度を合わせることである．問題(3)は，AS-ISモデルと参照モデルを比較し，差異を自動的に抽出することである．本論文では，問題(1)と(2)を解決するためにSCORオントロジーに基づく生産管理プロセスモデリング支援ツール（モデリング支援ツール）を実装した．ここで，SCORオントロジーとはSCORモデルの構成要素を計算機可読な形式で体系化したものを意味する．モデリング支援ツールの有効性を検証するために，ケーススタディとして，ある企業の機械部品製造現場を取り上げた．そこで，SCORオントロジーは，生産管理プロセスの中でも受注生産に限定して構築した．ケーススタディにより，モデリング支援ツールを用いて，「現場のAS-ISモデル」を作成可能であることを確認した．さらに，SCORプロセスを基に作成された現場のAS-ISモデルを，参照モデルと比較するための抽象化が，計算機可読なSCORオントロジーとモデルを活用することによって自動化できた．

## 関連論文
* <u>森田 武史</u>，洪 潤基，斎藤 忍，飯島 正，山口 高平，"SCOR オントロジーに基づく生産管理プロセスモデリング支援ツールの実装"，情報システム学会誌，Vol.11 No.1 pp.13-47 (2015) DOI: [10.19014/jissj.11.1_13](http://doi.org/10.19014/jissj.11.1_13)


# <a id="section-9">大規模Linked Open Dataのための日本語語彙の構築</a>
## 概要
本論文では，はじめに，大規模な LOD 構築手法とし て，日本語 Wikipedia オントロジーの LOD 化に向けた取 り組みを述べる．次に，構築した日本語 Wikipedia オン トロジー LOD が持つ，多くのプロパティと Linked Open Vocabularies に存在する語彙の対応付けを行うことで， 半自動的に日本語 LOD のためのプロパティの発見と日本語化を行った．最後に，対応付けを行ったプロパティと schema.org の語彙を比較することで，汎用的な日本語語彙としての有用性を示し，日本語 Wikipedia オントロジー の日本語 LOD ハブとしての有用性を示した．

## Related paper
* 玉川 奨，香川 宏介，<u>森田 武史</u>，山口 高平，"大規模Linked Open Dataのための日本語語彙の構築"，人工知能学会論文誌, Vol. 29 No.4 pp.386-395 (2014) DOI: [10.1527/tjsai.29.386](http://doi.org/10.1527/tjsai.29.386)

# <a id="section-8">Building up a class hierarchy with properties by refining and integrating Japanese Wikipedia Ontology and Japanese WordNet</a>
## Abstract
Previously, we constructed the Japanese Wikipedia Ontology (JWO) via a semi-automatic process using the Japanese Wikipedia, but it had problems due to a lack of upper classes and appropriate definitions of properties. Thus, the aim of the current study was to complement the upper classes in JWO by refining and integrating JWO and Japanese WordNet (JWN) to build a class hierarchy with defined properties based on the considerations of property inheritance. To achieve this, we developed tools that help users to refine the class-instance relationships, to identify the JWO classes that need to be aligned with JWN synsets, and to align the JWO classes with the JWN synsets via user interaction. We also integrated JWO and JWN using a domain ontology development environment, DODDLE-OWL. We also propose a method for building a class hierarchy with defined properties by elevating the common properties defined in sibling classes to higher classes in JWO.

## Related paper
* <u>Takeshi Morita</u>, Yuka Sekimoto, Susumu Tamagawa and Takahira Yamaguchi, "Building up a class hierarchy with properties by refining and integrating Japanese Wikipedia Ontology and Japanese WordNet", Web Intelligence and Agent Systems: An International Journal, Volume 12, Number 2, pp. 211-233, IOS Press (2014) DOI: [10.3233/WIA-140293](http://dx.doi.org/10.3233/WIA-140293)

## Software
* [JWO Refinement Tools](http://wikipedia-ontology.github.io/JWO_Refinement_Tools/)

# <a id="section-7">WikiBOKを用いた社会情報学の知識体系構築実験</a>
## 概要
本論文は，社会情報学のような新生学問分野の知識体系(body of knowledge, BOK)を，その学問分野を標榜する学部のカリキュラムから，知の構築支援システムWikiBOKを用いて，人々が協働して集合知としてそれを策定することに，初めて成功した我々の先駆的実験結果を報告している．この手法は，カリキュラムをリバースエンジニアリングの考え方で分析し，BOKの構成要素候補を抽出し，それをWikiBOKのもとで教員が協働して編集し，当該学問分野のBOKを策定する．実際に青山学院大学社会情報学部が展開しているカリキュラムを分析して協働作業を行なった結果，そのBOKは11個のエリアからなっていることを明らかにすることができた．従来，カリキュラムの科目群をクラスタリングして，BOKを求めようとする研究があったが，そのアプローチではBOKは策定できない．本論文で提案する手法を使うと，WikiBOKの援用により，さまざまな学問分野の知識体系を集合知として策定することが期待できる．

## 関連論文
* 増永 良文, 石田 博之, 伊藤 一成, 伊藤 守, 清水 康司, 荘司 慶行, 千葉 正喜, 長田 博泰, 福田 亘孝, 正村 俊之, <u>森田 武史</u>, 矢吹 太朗，"WikiBOKを用いた社会情報学の知識体系構築実験"，日本データベース学会論文誌 Vol.12 No.1 pp.133-138 (2013)

## Software
* [WikiBOK](https://github.com/WikiBok)

# <a id="section-6">日本語Wikipediaからプロパティを備えたオントロジーの構築</a>
## 概要
我々はこれまで，日本語 Wikipedia における様々なリソース (カテゴリツリー，一覧記事，リダイレクトリンク，Infobox) から，概念および概念間の関係 (Is-a 関係，クラス-インスタンス関係，プロパティ定義域，プロパティ値域，同義語，インスタンス間関係) を抽出し，高精度かつ大規模な汎用オントロジー (以下，日本語 Wikipedia オントロジー) を学習する手法を提案してきた ．しかし，プロパティ定義において，いくつかの課題が残っていた．そこで本稿では，これまでの手法に加えて，プロパティ名とトリプル数の増加を図るために，記事のリスト構造のスクレイピングを行った．次に，過去に提案した Infobox からのプロパティ抽出法 により抽出したプロパティ名と今回新たに抽出したプロパティ名を照合し，プロパティ間の上位下位関係を抽出した．抽出したトリプルから，プロパティ関係として対称関係，推移関係，関数関係，逆関数関係の推定を試みた．さらに，プロパティ定義域の洗練をするために，プロパティ定義域の親クラスと兄弟クラスを参照し，定義域のリフトアップを行った.

## 関連論文
* 玉川 奨, <u>森田 武史</u>, 山口 高平，"日本語Wikipediaからプロパティを備えたオントロジーの構築"，人工知能学会論文誌 Vol.26 No.4 pp.504-517 (2011) DOI: [10.1527/tjsai.26.504](http://dx.doi.org/10.1527/tjsai.26.504)

# <a id="section-5">Wikipediaを活用したセマンティックWebコンテンツの半自動構築およびWeb APIの実装</a>
近年，ハイパーリンクやフィードを活用した半構造化情報資源が広がりをみせている．中でも即時更新性・語彙網羅性に優れたオンライン百科事典Wikipediaがその代表例であり，セマンティックWebコンテンツ構築のためのリソースとして注目を集めている．しかしながら，Wikipediaはユーザ参加型という性質上，厳密な体系化が行われていないため，セマンティックWebコンテンツへ直接結び付けることは困難である．

本研究では，WikipediaからセマンティックWebコンテンツを半自動的に構築する手法を提案し，様々なソフトウェアから活用できるようにWeb APIとして実装することを目的とした．本研究により提供されるWeb APIは，Webサービスにおける入出力データの意味づけ（セマンティックWebサービス），ソーシャルタギングにおけるタグへの意味づけ（セマンティックソーシャルタギング），Webページへのアノテーションなどに活用可能な，セマンティックWebにおける意味基盤となるものである．網羅性の高いWikipediaから構築されたセマンティックWebコンテンツが，上記で示したような様々なアプリケーションから活用されることによって，アプリケーションを横断したデータ統合，分析，再利用などが容易になることが期待できる．

## 関連論文
* 2010年度　財団法人 電気通信普及財団 研究調査助成「Wikipediaを活用したセマンティックWebコンテンツの半自動構築およびWeb APIの実装」（研究代表：森田武史）

## Software
* [日本語Wikipediaオントロジー検索インタフェース＆Web APIs](https://github.com/t-morita/wikipedia_ontology_search)

# <a id="section-4">日本語Wikipediaからの大規模オントロジー学習</a>
## 概要
大規模なオントロジーの構築は情報検索やデータ統合 において有用であり， 日本語の大規模オントロジーとし ては日本語 WordNetや日本語語彙大系などが存在している．しかし，これらは手動で構築されており，構築コストが大きい. オントロジーの手動構築には，膨大な時間がかかり，間違いを起こしやすく，オントロジーの保守や更新が困難という問題がある．そこで，近年，オントロジー工学のコミュニティは，オン トロジー開発コストを削減するために，オントロジー学習 (Ontology Learning) と呼ばれる，(半)自動的にオントロジーを構築する手法，方法論，アルゴリズム，ツールなどの研究開発に取り組んできた．特に，フリーテキストからのオントロジー学習に関しては，機械学習，知識獲得，自然言語処理，情報検索など，様々な専門分野の手法を組み合わせた手法がこれまで数多く提案されている．しかしながら，非構造情報資源であるフリーテキストと構造情報資源であるオントロジーの間のギャップは大きく，高精度で，大規模なオントロジーを構築することは困難であるのが現状である．

一方，近年，Web 上の百科事典である Wikipedia が，新たな情報資源として注目を集めている．Wikipedia は語彙網羅性，即時更新性に優れており，半構造情報資源であることからフリーテキストと比べてオントロジーとのギャップが小さい．そのため，Wikipediaからのオントロジー学習研究が近年，盛んに行われている．しかしながら，Wikipedia はユーザ参加型という性質上，厳密な体系化が行われていないため，Wikipedia からの オントロジー学習にも，多くの課題が存在している．

本論文では，日本語Wikipedia をリソースとして，大規模かつ汎用的なオントロジー学習手法を提案した．さらに，提案するオントロジー学習手法を日本語 Wikipedia に適用し，構築したオントロジーを評価する事で，オントロジー構築リソースとしての Wikipedia の有用性を示す事を目標とした．

本論文では，Is-a 関係を抽出するために，Wikipedia カテゴリツリーに対して文字列処理，Infobox テンプレートとの照合処理，目次見出しのスクレイピングを行った． クラス-インスタンス関係を抽出するために，Wikipedia 一覧記事に対してスクレイピングを行う．Infobox をトリプルとして据えることで， プロパティの抽出を行い， 抽出した Is-a 関係とプロパティとの関係に着目することで， プロパティ定義域の獲得を試みた．さらにリダイレクトリンクを用いて同義語の抽出を行った．以上のような手法により，大規模かつ汎用的なオントロジー (Wikipedia オントロジー) 学習を行い，その評価を行った．

## 関連論文
* 玉川 奨，桜井 慎弥，手島 拓也，<u>森田 武史</u>，和泉 憲明，山口 高平，"日本語Wikipediaからの大規模オントロジー学習"，人工知能学会論文誌 Vol. 25 No.5 pp.623-636 (2010) DOI: [10.1527/tjsai.25.623](http://dx.doi.org/10.1527/tjsai.25.623)

# リソース
* [日本語Wikipediaオントロジー](https://osdn.jp/projects/wikipedia-ont/)

# <a id="section-3">エンタープライズアプリケーションオントロジーに基づく業務アプリケーション開発支援</a>
## 概要
近年，情報システムやその仕様の大規模化および複雑化は，設計や開発に関する専門知識を持たない利用者と，業務の詳細を把握しきれない設計者や開発者との間において，開発に関する情報を適切に把握することを困難にしている．そこで，情報システムの構築には，利用者と設計者，開発者による共通理解や情報共有が重要との観点から，本研究では，オントロジーに基づいた情報システムの開発支援法を提案した．ここで，一般に，情報システムの開発では対象業務を適切に把握すことが不可欠であり，このためには，業務に用いられる帳票や業務定義を援用するための用語集のほかに，業務手順を与えるユースケース記述や業務の流れを与える業務フロー，業務の規約を与える法律や規定，規則など，さまざまな情報が必要になる．このために，このような要求仕様に関する情報を，単一のオントロジーとして構造化することは困難である．そこで，本手法では，Webアプリケーションに限定するものの，情報システムの開発に必要な情報を，構造的構成と動作的構成，規約的構成という三つの視点から分析し，それぞれを構成要素としたエンタープライズアプリケーションオントロジー(EAO)を定義している．そして，EAOの構成要素を用いて，Webアプリケーションの画面遷移構造を記述することにより，情報システムの開発仕様として必要な要素を表形式で一元的に記述する．この一元化されたWebアプリケーションの仕様を，本研究では，Webプロセス定義として定め，これによって，画面遷移の粒度でユーザと設計者・開発者が共通理解することが可能となる．最終的には，Webプロセス定義に基づいて，開発者はWebアプリケーションを実装し，ユーザは実装結果を確認する．本研究では，ケーススタディとして，提案手法を自治体における台帳管理業務システムの開発に適用した．そして，実際の開発プロジェクトにおいて計測を行い，アプリケーション開発の上流工程において，ステークホルダー間での合意形成に必要十分な情報は何であるかを具体的に定義し，オントロジー利用の効果を実証した．

## 関連論文
*  近藤 恵一, <u>森田 武史</u>, 和泉 憲明, 橋田 浩一, 山口 高平, "エンタープライズアプリケーションオントロジーに基づく業務アプリケーション開発支援", 人工知能学会論文誌 Vol.23 No.6 pp.473-484 (2008)  DOI: [10.1527/tjsai.23.473](http://dx.doi.org/10.1527/tjsai.23.473)

# <a id="section-2">DODDLE-OWL: Interactive Domain Ontology Development with Open Source Software in Java</a>
## Abstract
In this paper, we propose an interactive domain ontology development environment called DODDLE-OWL. DODDLE-OWL refers to existing ontologies and supports the semi-automatic construction of taxonomic and other relationships in domain ontologies from documents. Integrating several modules, DODDLE-OWL is a practical and interactive domain ontology development environment. In order to evaluate the efficiency of DODDLE-OWL, we compared DODDLE-OWL with popular manual-building method. In order to evaluate the scalability of DODDLE-OWL, we constructed a large sized ontology over 34,000 concepts in the field of rocket operation using DODDLE-OWL. Through the above evaluation, we confirmed the efficiency and the scalability of DODDLE-OWL. Currently, DODDLE-OWL is open source software in Java and has 100 and more users from 20 and more countries.

## Related paper
* <u>Takeshi Morita</u>, Noriaki Izumi, Naoki Fukuta, Takahira Yamaguchi, "DODDLE-OWL: Interactive Domain Ontology Development with Open Source Software in Java", IEICE Transactions on Information and Systems, Special Issue on Knowledge-Based Software Engineering Vol.E91-D No.4 pp.945-958 (2008) DOI: [10.1093/ietisy/e91-d.4.945](http://dx.doi.org/10.1093/ietisy/e91-d.4.945)

## Software
* [DODDLE-OWL (a Domain Ontology rapiD DeveLopment Environment - OWL extension)](https://github.com/doddle-owl/DODDLE-OWL)

# <a id="section-1">A Graphical RDF-based Meta-Model Management Tool</a>
## Abstract
We propose a tool to manage several sorts of relationships among RDF (Resource Description Framework) and RDFS (RDF Schema). Our tool consists of three main functions: graphical editing of RDF descriptions, graphical editing of RDFS descriptions, and meta-model management facilities. In this paper, we focus on the meta-model management, a key concept which is defined as the appropriate management of the correspondence between a model and its meta-model: especially, the class and property in the meta-model, and the type of RDF resource and property in the model. The above facilities are implemented based on the plug-in system. We provide basic plug-in modules for checking the consistency of RDFS classes and properties. The prototyping tool, called MR<sup>3</sup> (Meta-Model Management based on RDFs Revision Reflection), is implemented by Java language. Through an experiment using MR<sup>3</sup>, we show how MR<sup>3</sup> contributes to the Semantic Web paradigm from the standpoint of RDFs description management.

## Related paper
* <u>Takeshi Morita</u>, Noriaki Izumi, Naoki Fukuta, Takahira Yamaguchi, "A Graphical RDF-based Meta-Model Management Tool", IEICE Transactions on Information and Systems, Special Issue on Knowledge-Based Software Engineering Vol.E89-D No.4 pp.1368-1377 (2006)  DOI: [10.1093/ietisy/e89-d.4.1368](http://dx.doi.org/10.1093/ietisy/e89-d.4.1368)

## Software
* [MR<sup>3</sup> (Meta-Model Management based on RDFs Revision Reflection)](http://mr-3.github.io)

