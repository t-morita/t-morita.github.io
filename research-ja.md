---
layout: ja_page
ja_title: 研究内容
permalink: /research-ja/
---
現在のWeb コンテンツは，人間が理解することを目的として構築されているため，ソフトウェアによる理解は困難です．一方，次世代Web の候補の一つであるセマンティックWeb は，ソフトウェアが意味理解可能な辞書（オントロジー）に基づいて，Web コンテンツにソフトウェア可読なメタデータを付与することによって，ソフトウェアがWeb コンテンツを理解し，推論することを可能にしようという試みです．セマンティックWeb の実現により，知的な情報検索やアプリケーションを横断したデータ統合および再利用などが可能になることが期待されています．しかしながら，ソフトウェアがWeb コンテンツを理解するためのセマンティックWeb標準技術である，RDF，RDFS，OWLにより記述されるセマンティックWeb コンテンツの構築には，多大なコストを要しています．以上の背景より，セマンティックWebコンテンツの構築コストを低減するために，セマンティックWeb コンテンツ構築支援に関する研究にこれまで主に従事してきました．これまでに取り組んできた主な研究テーマとその概要は，以下のとおりです．

# 2015年ー現在：知能アプリケーション開発プラットフォームPRINTEPSの開発
Under Construction

# 2012年ー現在 SCOR：オントロジーに基づく生産管理プロセスモデリング支援ツールの実装
Under Construction

# 2013年ー現在：PT調査自動化に関する研究
Under Construction

# 2011年ー現在：プロパティスキーマ半自動構築に関する研究
Under Construction

# 2011年ー2013年：学際的学問分野のＢＯＫ策定を事例とした知の創成と検証支援システムの研究・開発
Under Construction

# 2010年ー2014年：Linked Dataを用いたモビリティサービスの開発
Under Construction

# 2009年ー2010年：Wikipediaを活用したセマンティックWebコンテンツの半自動構築およびWeb APIの実装
近年，ハイパーリンクやフィードを活用した半構造化情報資源が広がりをみせています．中でも即時更新性・語彙網羅性に優れたオンライン百科事典Wikipediaがその代表例であり，セマンティックWebコンテンツ構築のためのリソースとして注目を集めています．しかしながら，Wikipediaはユーザ参加型という性質上，厳密な体系化が行われていないため，セマンティックWebコンテンツへ直接結び付けることは困難です．本研究では，WikipediaからセマンティックWebコンテンツを半自動的に構築する手法を提案し，様々なソフトウェアから活用できるようにWeb APIとして実装することを目的とします．本研究により提供されるWeb APIは，Webサービスにおける入出力データの意味づけ（セマンティックWebサービス），ソーシャルタギングにおけるタグへの意味づけ（セマンティックソーシャルタギング），Webページへのアノテーションなどに活用可能な，セマンティックWebにおける意味基盤となるものです．網羅性の高いWikipediaから構築されたセマンティックWebコンテンツが，上記で示したような様々なアプリケーションから活用されることによって，アプリケーションを横断したデータ統合，分析，再利用などが容易になることが期待できます．Wikipediaオントロジーを検索するためのAPIおよび検索インタフェースは，以下のWebサイトで公開しています．(<https://github.com/t-morita/wikipedia_ontology_search>)．

## 関連論文
* 森田 武史, 桜井 慎弥, 玉川 奨, 和泉 憲明, 山口 高平, "日本語Wikipediaオントロジーの構築および検索システムの実装", 情報システム学会，第5回全国大会・研究発表大会, (2009.12)

# 2008年－2010年：日本語Wikipediaからの大規模オントロジー学習
Wikipedia は語彙網羅性および即時更新性に優れており，半構造情報資源であることからフリーテキストと比べてオントロジーとのギャップが小さいです．そのため，Wikipedia からのオントロジー学習研究が近年，盛んに行われています．しかしながら，Wikipedia はユーザ参加型という性質上，厳密な体系化が行われていないため，Wikipediaからのオントロジー学習には，多くの課題が存在しています．以上より，日本語Wikipedia における様々なリソース（カテゴリツリー，一覧記事，リダイレクトリンク，Infobox, Infoboxテンプレート）から，大規模かつ汎用的なオントロジーを学習する手法を提案しました．構築したオントロジーおよび日本語Wikipediaからのオントロジー学習ツールは，SourceForge.jpに公開しました(<http://wikipedia-ont.sourceforge.jp/>)．

## 関連論文
* 玉川 奨, 森田 武史, 山口 高平, "日本語Wikipediaからプロパティを備えたオントロジーの構築", 人工知能学会論文誌 Vol.26 No.4 pp.504-517, (2011.7) 
* 玉川 奨, 桜井 慎弥, 手島 拓也, 森田 武史, 和泉 憲明, 山口 高平, "日本語Wikipediaからの大規模オントロジー学習", 人工知能学会論文誌 論文特集「2009年度全国大会近未来チャレンジ」 Vol.25 No.5 pp.623-636, (2010.11) 
* Susumu Tamagawa, Shinya Sakurai, Takuya Tejima, Takeshi Morita, Noriaki Izumi, Takahira Yamaguchi, "Learning a Large Scale of Ontology from Japanese Wikipedia", 2010 IEEE/WIC/ACM International Conference on Web Intelligence pp.279-286, (2010.9) 

# 2006年ー2007年：エンタープライズアプリケーションオントロジーに基づく業務アプリケーション開発支援
近年，情報システムやその仕様の大規模化および複雑化は，設計や開発に関する専門知識を持たない利用者と，業務の詳細を把握しきれない設計者や開発者との間において，開発に関する情報を適切に把握することを困難にしています．そこで，情報システムの構築には，利用者と設計者，開発者による共通理解や情報共有が重要との観点から，本研究では，オントロジーに基づいた情報システムの開発支援法を提案しました．ここで，一般に，情報システムの開発では対象業務を適切に把握すことが不可欠であり，このためには，業務に用いられる帳票や業務定義を援用するための用語集のほかに，業務手順を与えるユースケース記述や業務の流れを与える業務フロー，業務の規約を与える法律や規定，規則など，さまざまな情報が必要になります．このために，このような要求仕様に関する情報を，単一のオントロジーとして構造化することは困難です．そこで，本手法では，Webアプリケーションに限定するものの，情報システムの開発に必要な情報を，構造的構成と動作的構成，規約的構成という三つの視点から分析し，それぞれを構成要素としたエンタープライズアプリケーションオントロジー(EAO)を定義しています．そして，EAOの構成要素を用いて，Webアプリケーションの画面遷移構造を記述することにより，情報システムの開発仕様として必要な要素を表形式で一元的に記述します．この一元化されたWebアプリケーションの仕様を，本研究では，Webプロセス定義として定め，これによって，画面遷移の粒度でユーザと設計者・開発者が共通理解することが可能となります．最終的には，Webプロセス定義に基づいて，開発者はWebアプリケーションを実装し，ユーザは実装結果を確認します．本研究では，ケーススタディとして，提案手法を自治体における台帳管理業務システムの開発に適用しました．そして，実際の開発プロジェクトにおいて計測を行い，アプリケーション開発の上流工程において，ステークホルダー間での合意形成に必要十分な情報は何であるかを具体的に定義し，オントロジー利用の効果を実証しました．

## 関連論文
* 近藤 恵一, 森田 武史, 和泉 憲明, 橋田 浩一, 山口 高平, "エンタープライズアプリケーションオントロジーに基づく業務アプリケーション開発支援", 人工知能学会論文誌 論文特集「システム開発論文特集」 Vol.23 No.6 pp.473-484, (2008.11) 
* Keiichi Kondo, Shogo Hoshii, Takeshi Morita, Noriaki Izumi, Takahira Yamaguchi, "Semantics Driven Development of Software Systems Based on Business Ontologies", Proceedings of the Seventh Joint Conference on Knowledge-Based Software Engineering, Frontiers in Artificial Intelligence and Applications Vol.140 pp.176-185, (2006.8)

# 2004年－2007年：領域オントロジー構築支援環境の実装と評価
テキストや汎用オントロジーなどの既存情報資源から自動的に領域オントロジーを構築するために，多くの研究は，知識工学，自然言語処理，データマイニングの技術を用いています．しかしながら，領域オントロジーの構造は専門家の対象領域の見方に依存して変化するため，領域オントロジーを全自動で構築することは困難です．実用的な領域オントロジー構築支援を行うためには，全自動ではなく，ユーザとのインタラクションを通して，半自動的に領域オントロジーの構築を支援することが重要です．以上より，インタラクティブで実用的な領域オントロジー構築支援環境DODDLE-OWL (a Domain Ontology rapiD DeveLopment Environment - OWL extension) を提案しました. DODDLE-OWLは，領域専門文書を入力として，WordNet やEDR電子化辞書 などの既存オントロジーを参照しながら，領域オントロジーにおける階層関係およびその他（階層以外）の関係の半自動構築を支援します．実装したツールは，SourceForge.netに公開しました(<http://doddle-owl.org>)．

## 関連論文
* Takeshi Morita, Noriaki Izumi, Takahira Yamaguchi, "Integrating a Domain Ontology Development Environment and an Ontology Search Engine", Proceedings of the Eighth Joint Conference on Knowledge-Based Software Engineering, Frontiers in Artificial Intelligence and Applications pp.263-272, (2008.8) 
* Takeshi Morita, Noriaki Izumi, Naoki Fukuta, Takahira Yamaguchi, "DODDLE-OWL: Interactive Domain Ontology Development with Open Source Software in Java", IEICE Transactions on Information and Systems, Special Issue on Knowledge-Based Software Engineering Vol.E91-D No.4 pp.945-958, (2008.4) 
* 森田 武史, 和泉 憲明, 山口 高平, "オントロジー検索エンジンを用いた領域オントロジー構築支援環境 DODDLE-OWLの拡張", 人工知能学会 セマンティックWebとオントロジー研究会 第15回 SIG-SWO-A603-07, (2007.3)  
* Takeshi Morita, Naoki Fukuta, Noriaki Izumi, Takahira Yamaguchi, "DODDLE-OWL: A Domain Ontology Construction Tool with OWL", Proceedings of the 1st Asian Semantic Web Conference Lecture Notes in Computer Science Vol.4185 pp.537-551, (2006.9)

## ポスター発表
* Takeshi Morita, Takuya Tejima, Noriaki Izumi, Takahira Yamaguchi, "A Domain Ontology Construction Method Supported by an Ontology Search Engine", In Poster & Demonstration Proceedings of the 6th International Semantic Web Conference pp.73-74, (2007.11) 
* Takeshi Morita, Yoshihiro Shigeta, Naoki Sugiura, Naoki Fukuta, Noriaki Izumi, Takahira Yamaguchi, "DODDLE-OWL: On-the-fly Ontology Construction with Ontology Quality Management", Proceedings of the 3rd International Semantic Web Conference, Poster Abstracts pp.47, (2004.11)

# 2003年－2005年：RDF(S)コンテンツ構築支援ツールの実装と評価
RDF(S) コンテンツの構築を支援するために様々な研究が行われていますが，RDF コンテンツおよびRDFS コンテンツを同時に構築する際に生じる問題に焦点を絞った研究は行われていません．RDFコンテンツおよびRDFSコンテンツの間の意味的な対応をとらえるためには，より詳細なセマンティクスが必要となります．以上より，RDFコンテンツとRDFS コンテンツを分離し，両者の間の整合性を保ちながら視覚的に編集する機能を持つRDF(S) コンテンツ構築支援ツールMR<sup>3</sup> (Meta-Model Management based on RDFs Revision Reflection) を提案しました．実装したツールは，SourceForge.netに公開しています(<http://mrcube.org>)．

## 関連論文
* Takeshi Morita, Noriaki Izumi, Naoki Fukuta, Takahira Yamaguchi, "A Graphical RDF-based Meta-Model Management Tool", IEICE Transactions on Information and Systems, Special Issue on Knowledge-Based Software Engineering Vol.E89-D No.4 pp.1368-1377, (2006.4) 
* Takeshi Morita, Noriaki Izumi, Naoki Fukuta, Takahira Yamaguchi, "MR<sup>3</sup>: Meta-Model Management Based on RDFs Revision Reflection", Proceedings of the Joint Conference on Knowledge Based Software Engineering, Frontiers in Artificial Intelligence and Applications Vol.108 pp.228-236, (2004.8)

## ポスター発表
* Takeshi Morita, Noriaki Izumi, Naoki Fukuta, Takahira Yamaguchi, "Building up RDF and RDFS Descriptions with Meta-Model Management", Proceedings of the 4th International Semantic Web Conference, Poster PID28, (2005.11)  
* 森田 武史, 和泉 憲明, 福田 直樹, 山口 高平, "セマンティックWebのためのメタモデル管理ツール", 第17回 人工知能学会全国大会論文集 1G2-05, (2003.6) 
