---
layout: page
title: Research
permalink: /research/
---

* [Integrating Smart Glasses with Question-Answering Module in Assistant Work Environment](#section-13)
* [Implementing Mobility Service with Japanese Linked Data](#section-12)
* [Identifying Behavior Objective from Traffic Behavior Log Data by Using Facility Ontology](#section-11)
* [Diet Therapy Service Based on the Integration of Linked Data and Rule Base](#section-10)
* [A Support Tool for Production Management Process Modeling based on SCOR Ontology](#section-9)
* [Building up Japanese Vocabulary for Large Scale Linked Open Data](#section-8)
* [Building up a class hierarchy with properties by refining and integrating Japanese Wikipedia Ontology and Japanese WordNet](#section-7)
* [An Experimental Result of the Body of Knowledge Formulation of Social Informatics using WikiBOK](#section-6)
* [Building up Ontologies with Many Properties from Japanese Wikipedia](#section-5)
* [Learning a Large Scale of Ontology from Japanese Wikipedia](#section-4)
* [Development Support of Business Application Based on Enterprise Application Ongology](#section-3)
* [DODDLE-OWL: Interactive Domain Ontology Development with Open Source Software in Java](#section-2)
* [A Graphical RDF-based Meta-Model Management Tool](#section-1)

# <a id="section-13">Integrating Smart Glasses with Question-Answering Module in Assistant Work Environment</a>
## Abstract
Recently, smart glasses have been applied in field work, with which a worker goes well during work by contacting a support operator from a remote location. The worker, however, cannot go well if the support operator is not there. To solve the issues, the paper discusses how a work system should be developed by integrating smart glasses with a question-answering module. We design the work knowledge acquired from skilled people and manuals as a work flow, rule base, goal tree, domain ontologies and RDF data. Workers follow work process by referring to the work flow, referring to multimedia, and receiving answers from the question-answering module incorporated with a knowledge base for questions that are raised during the work. The authors conducted a demonstration experiment and found that workers could perform the work more autonomously by importing the system.

## Related paper
* Ryutaro Nambu, <u>Takeshi Morita</u>, Takahira Yamaguchi, "Integrating Smart Glasses with Question-Answering Module in Assistant Work Environment", The Review of Socionetwork Strategies, Vol. 11, Issue 1, pp. 1-16 (2017) [10.1007/s12626-017-0003-4](https://doi.org/10.1007/s12626-017-0003-4)

# <a id="section-12">Implementing Mobility Service with Japanese Linked Data</a>
## Abstract
This study aims at developing a web service with Japanese Linked Data and evaluating the service. Recently, Japanese government has set open data as a new strategy in information technology field and focuses on 'Linked Open Data (LOD)' as a means to publish. However, the number of dataset as Japanese Linked Data is small, and the effect by introducing Japanese Linked Data has not been shown yet. Therefore, we created Japanese Linked Data focused on geographical or positional data, and implemented a mobility service to reduce user's cognitive load. Moreover, we conducted verification experiment for using the service and compared with conventional services. As a result, the possibilities of Linked Data to respond to various queries easily and to apply for information services by crossing some domains were explored.

## Related paper
* <u>Takeshi Morita</u>, Chie Iijima, Wataru Okawara, Yoshitaro Enomoto, Takahira Yamaguchi, "Implementing Mobility Service with Japanese Linked Data", International Journal of Computational Intelligence Studies, Vol. 5, No. 3/4, pp.267-288 (2016) DOI: [10.1504/IJCISTUDIES.2016.083573](https://doi.org/10.1504/IJCISTUDIES.2016.083573)

# <a id="section-11">Identifying Behavior Objective from Traffic Behavior Log Data by Using Facility Ontology</a>
## Abstract
Traffic behaviour surveys by hand require both a lot of money and human resources. Recently, traffic behaviour surveys using information technology have been carried out. In this study, we propose a method to extract staying points from GPS-based positional data, to identify the types of staying facilities by using Google Places API, a facility ontology, the regularity which is analysed from trip chains about traffic behaviour and to determine the behaviour objectives based on the rules between the behaviour objectives and the types of staying facilities. This method could identify 67.9% behaviour objectives in the evaluation using GPS location data from the traffic behaviour survey in Nagasaki.

## Related paper
* Yu Sugawara, <u>Takeshi Morita</u>, Hidenao Abe, Shuichi Matsumoto and Takahira Yamaguchi，"Identifying Behavior Objective from Traffic Behavior Log Data by Using Facility Ontology", Special Issue on Data Mining and Service Science for Innovation, International Journal of Knowledge Engineering and Soft Data Paradigms, Vol. 5, No.2, pp.68-84 (2016) DOI: [10.1504/IJKESDP.2016.075975](http://dx.doi.org/10.1504/IJKESDP.2016.075975)

# Software
* [SmaphoProbe](https://github.com/smaphoprobe/SmaphoProbe)


# <a id="section-10">Diet Therapy Service Based on the Integration of Linked Data and Rule Base</a>
## Abstract
As Linked Data consumption has not yet been discussed from the points of information services, we discuss here how to build web applications with function extendibility and service maintainability, integrating Linked Data and rule bases. The function extendibility has been done with less cost just by linking original Linked Data and other Linked Data. The service maintainability has been done just by exchanging initial rules for given task with other rules for another task. Using the framework, we have implemented web application for diet therapy and then discussed how well the diet therapy service goes well with the questionnaire survey of a diabetic.

## Related paper
*	Yusuke Tagawa, Arata Tanaka, <u>Takeshi Morita</u>, Hiroya Minami, Daichi Namikawa, Michio Shimomura, Takahira Yamaguchi, "Diet Therapy Service Based on the Integration of Linked Data and Rule Base", Transactions of the Japanese Society for Artificial Intelligence, Vol.31, No1 pp.16-28, (2016)  DOI: [10.1527/tjsai.31-1_LOD-B](http://dx.doi.org/10.1527/tjsai.31-1_LOD-B)

# <a id="section-9">A Support Tool for Production Management Process Modeling based on SCOR Ontology</a>
## Abstract
In this research, we propose a method and a tool to detect the difference between as-is models and reference models. The tool supports factory management to recognize pros and cons of the as-is model, and to understand current conditions. We use the supply-chain operations reference-model (SCOR model) as a specific reference model that covers supply chain management. There are three main problems to be solved in order to achieve our goal. The first problem is to make as-is model and reference-model described by a machine-readable format. The second problem is to adjust the abstraction level of the as-is model and the reference model. The third problem is to extract the difference automatically by comparing the as-is model and the reference model. In this paper, we propose a support tool for the production management process modeling based on SCOR ontology in order to solve the first and second problems. SCOR ontology means the building blocks of the SCOR model (concepts and relationships between the concepts related to production management) described by a machine-readable format. In order to verify the effectiveness of our proposed tool, we used it to make production management processes in a manufacturing company. We confirmed that our tool could appropriately make the as-is model. In addition, we could adjust the abstraction level between the as-is model and the reference model automatically by using a machine-readable SCOR ontology and the model.

## Related paper
* <u>Takeshi Morita</u>, Yunki Hong, Shinobu Saito, Tadashi Iijima, Takahira Yamaguchi, "A Support Tool for Production Management Process Modeling based on SCOR Ontology", JISSJ Vol.11 No.1 pp.13-47 (2015) DOI: [10.19014/jissj.11.1_13](http://doi.org/10.19014/jissj.11.1_13)


# <a id="section-8">Building up Japanese Vocabulary for Large Scale Linked Open Data</a>
## Abstract
Here is discussed how to build up Japanese vocabulary for Japanese Linked Open Data. The vocabulary is constructed by mapping properties of the Japanese Wikipedia Ontology to the Linked Open Vocabularies. The Japanese Wikipedia Ontology is a large scale ontology learned from the Japanese Wikipedia. It includes many properties and property relations (property domains and property ranges). The Linked Open Vocabularies is a large cloud for vocabularies of Linked Open Data. We construct a Japanese vocabulary semi-automatically by mapping properties to vocabularies. Experimental case studies show us that we can use the built Japanese vocabulary as a general vocabulary for building Japanese Linked Open Data.

## Related paper
* Susumu Tamagawa, Kosuke Kagawa, <u>Takeshi Morita</u>, Takahira Yamaguchi, "Building up Japanese Vocabulary for Large Scale Linked Open Data", Transactions of the Japanese Society for Artificial Intelligence Vol.29 No.4 pp.386-395 (2014) DOI: [10.1527/tjsai.29.386](http://doi.org/10.1527/tjsai.29.386)

# <a id="section-7">Building up a class hierarchy with properties by refining and integrating Japanese Wikipedia Ontology and Japanese WordNet</a>
## Abstract
Previously, we constructed the Japanese Wikipedia Ontology (JWO) via a semi-automatic process using the Japanese Wikipedia, but it had problems due to a lack of upper classes and appropriate definitions of properties. Thus, the aim of the current study was to complement the upper classes in JWO by refining and integrating JWO and Japanese WordNet (JWN) to build a class hierarchy with defined properties based on the considerations of property inheritance. To achieve this, we developed tools that help users to refine the class-instance relationships, to identify the JWO classes that need to be aligned with JWN synsets, and to align the JWO classes with the JWN synsets via user interaction. We also integrated JWO and JWN using a domain ontology development environment, DODDLE-OWL. We also propose a method for building a class hierarchy with defined properties by elevating the common properties defined in sibling classes to higher classes in JWO.

## Related paper
* <u>Takeshi Morita</u>, Yuka Sekimoto, Susumu Tamagawa and Takahira Yamaguchi, "Building up a class hierarchy with properties by refining and integrating Japanese Wikipedia Ontology and Japanese WordNet", Web Intelligence and Agent Systems: An International Journal, Volume 12, Number 2, pp. 211-233, IOS Press (2014) DOI: [10.3233/WIA-140293](http://dx.doi.org/10.3233/WIA-140293)

## Software
* [JWO Refinement Tools](http://wikipedia-ontology.github.io/JWO_Refinement_Tools/)

# <a id="section-6">An Experimental Result of the Body of Knowledge Formulation of Social Informatics using WikiBOK</a>
## Abstract
This paper reports on the results of a pioneering experiment to formulate a body of knowledge (BOK) of a new academic field, such as social informatics, as a collective intelligence using WikiBOK - a BOK formulation-aid system. Our approach was based on a reverse engineering analysis of an institution's curriculum, such that a set of BOK element candidates were extracted and used to formulate a BOK of the target field collectively using WikiBOK. The method was applied to create a BOK of the School of Social Informatics at Aoyama Gakuin University, revealing that it consisted of eleven distinct areas (or disciplinary subfields). The reverse engineering approach showed that the traditional approach of obtaining a BOK through clustering a set of course works was unsuccessful. Alternativly, it is expected that through the adoption of our approach, anyone will be able to construct a BOK of a particular discipline of interest.

## Related papers
* Taro Yabuki, <u>Takeshi Morita</u>, Yoshifumi Masunaga, "Formulation and Verification of the Body of Knowledge of New Discipline using WikiBOK", Proceedings of the 9th International Conference on Ubiquitous Information Management and Communication, a76 (2015) DOI: [10.1145/2701126.2701188](http://dx.doi.org/10.1145/2701126.2701188)
* Yoshifumi MASUNAGA, Hiroyuki ISHIDA, Kazunari ITO, Mamoru ITO, Yasushi SHIMIZU, Yoshiyuki SHOJI, Toru TAKAHASHI, Masaki CHIBA, Hiroyasu NAGATA, Nobutaka FUKUDA, Toshiyuki MASAMURA, <u>Takeshi MORITA</u>, Taro YABUKI, "An Experimental Result of the Body of Knowledge Formulation of Social Informatics using WikiBOK", DBSJ Journal Vol.12 No.1 pp.133-138 (2013)

## Software
* [WikiBOK](https://github.com/WikiBok)

# <a id="section-5">Building up Ontologies with Many Properties from Japanese Wikipedia</a>
## Abstract
Here is discussed how to build up ontologies with many properties from Japanese Wikipedia. The ontologies include is-a relationship (rdfs:subClassOf), class-instance relationship (rdf:type) and synonym relation (skos:altLabel) moreover it includes property relations and types. Property relations are triples, property domain (rdfs:domain) and property range (rdfs:range). Property types are object (owl:ObjectProperty), data (owl:DatatypeProperty), symmetric (owl:SymmetricProperty), transitive (owl:TransitiveProperty), functional (owl:FunctionalProperty) and inverse functional (owl:InverseFunctionalProperty). Experimental case studies show us that the built Japanese Wikipedia Ontology goes better than DBpedia from utility when we use, such as Hub of Linked Data, especially in Japan.

## Related papers
* Susumu Tamagawa, <u>Takeshi Morita</u>, Takahira Yamaguchi, "Building up Ontologies with Many Properties from Japanese Wikipedia", Transactions of the Japanese Society for Artificial Intelligence Vol.26 No.4 pp.504-517 (2011) DOI: [10.1527/tjsai.26.504](http://dx.doi.org/10.1527/tjsai.26.504)
*  Susumu Tamagawa, <u>Takeshi Morita</u>, Takahira Yamaguchi, "Extracting Property Semantics from Japanese Wikipedia", The 2012 International Conference on Active Media Technology, LNCS7669, pp.357-368 (2012) DOI: [10.1007/978-3-642-35236-2_36](http://doi.org/10.1007/978-3-642-35236-2_36)

# <a id="section-4">Learning a Large Scale of Ontology from Japanese Wikipedia</a>
## Abstract
Here is discussed how to learn a large scale of ontology from Japanese Wikipedia. The learned ontology includes the following properties: rdfs:subClassOf (IS-A relationship), rdf:type (class-instance relationship), owl:Object/DatatypeProperty (Infobox triple), rdfs:domain (property domain), and skos:altLabel (synonym). Experimental case studies show us that the learned Japanese Wikipedia Ontology goes better than already existing general linguistic ontologies, such as EDR and Japanese WordNet, from the points of building costs and structure information richness.

## Related papers
* Susumu Tamagawa, Shinya Sakurai, Takuya Tejima, <u>Takeshi Morita</u>, Noriaki Izumi, Takahira Yamaguchi, "Learning a Large Scale of Ontology from Japanese Wikipedia", Transactions of the Japanese Society for Artificial Intelligence Vol.25 No.5 pp.623-636 (2010) DOI: [10.1527/tjsai.25.623](http://dx.doi.org/10.1527/tjsai.25.623)
* Susumu Tamagawa, Shinya Sakurai, Takuya Tejima, <u>Takeshi Morita</u>, Noriaki Izumi, and Takahira Yamaguchi, "Learning a Large Scale of Ontology from Japanese Wikipedia", 2010 IEEE/WIC/ACM International Conference on Web Intelligence, pp.279-286 (2010) DOI: [10.1109/WI-IAT.2010.177](http://dx.doi.org/10.1109/WI-IAT.2010.177)

# Resource
* [Japanese Wikipedia Ontology](https://osdn.jp/projects/wikipedia-ont/)

# <a id="section-3">Development Support of Business Application Based on Enterprise Application Ongology</a>
## Abstract
In this paper, we propose a supporting method for developments of Web applications in order to support communication between users and developers. Our method combines three-layer architecture modeling of Web application and knowledge sharing technologies based on ontologies. The ontologies, which are used in the method and called enterprise application ontology (EAO), enable users and developers to form common understanding about system specification. EAO covers three aspects (legal aspect, business process, and software design) of business which is a candidate of development of a Web application. EAO includes three ontologies constructed from each of the three aspects. Concepts and structure of EAO are applied on page transition models, which are called Web Process Architecture, of a Web application. As a case study, we applied our method for a development of a ledger accounting system in a local government. And we confirmed that our method could support the development on the business analysis phase.

## Related papers
*  Keiichi Kondo, <u>Takeshi Morita</u>, Noriaki Izumi, Kôiti Hasida, Takahira Yamaguchi, "Development Support of Business Application Based on Enterprise Application Ongology", Transactions of the Japanese Society for Artificial Intelligence Vol.23 No.6 pp.473-484 (2008) DOI: [10.1527/tjsai.23.473](http://dx.doi.org/10.1527/tjsai.23.473)
* Keiichi Kondo, Shogo Hoshii, <u>Takeshi Morita</u>, Noriaki Izumi, Takahira Yamaguchi, "Semantics Driven Development of Software Systems Based on Business Ontologies", Proceedings of the Seventh Joint Conference on Knowledge-Based Software Engineering, Frontiers in Artificial Intelligence and Applications Vol.140 pp.176-185 (2006)

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
