---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
---

**Supporting Algorithm Accountability using Provenance — Opportunities and Challenges** is a half-day satellite event that is to take place as part of [Provenance Week 2018](http://provenanceweek2018.org) at King’s College London, 12 July, 2018. The workshop aims to bring together researchers from different research areas, including law, machine learning, ethics as well as provenance, to explore challenges and opportunities for provenance-based algorithm accountability.

Concerns about the fairness of computational algorithms are increasingly growing. It is widely recognised that algorithms are playing an important role in our life. And more of us are demanding more transparency regarding how our personal data might be processed and used by algorithms. This demand for transparency and accountability in algorithms is not new. It has been an active research topic in areas like Artificial Intelligence, Human Computer Interactions and etc. 

Provenance information has a long standing history in supporting scientific research and enhancing its rigour. Validating and enabling reproducibility of research results are part of the core motivations for provenance research. However, the potential role of provenance information in facilitating algorithm transparency and accountability is less known or well understood. Therefore, this half-day workshop aims to bring together researchers from different research areas, including law, machine learning, ethics as well as provenance, to explore challenges and opportunities for provenance-based algorithm accountability.

## Aims

The workshop has three primary goals:
* To solicit and discuss case studies that will benefit from provenance research and technologies for supporting algorithm accountability
* To facilitate research collaborations and initiatives between provenance researchers and researchers from other areas working on algorithm accountability
* To identify gaps and open challenges in provenance research to support algorithm accountability

## Organisers
* [Jun Zhao](https://sites.google.com/site/junzhaohome/), University of Oxford
* [Reuben Binns](https://www.reubenbinns.com), University of Oxford
* [Adriane Chapman](https://www.ecs.soton.ac.uk/people/ac1n16), University of Southampton

## Registration

If you are not participanting ProvWeek for the whole week, you can purchase a one-day ticket at £150. Registration information can be found [here](http://provenanceweek2018.org/registration/).

## When and Where
From 1:30pm to 5:30pm, 12 July, [Lecture Theatre 1, Bush House, King’s College London](http://provenanceweek2018.org/location/), 30 Aldwych, London, WC2B 4BG

## Tentative workshop programme

| **Time** 	            | **Activity**            	                
|-----------------------|-------------------------------------	
| **13:30 - 13:35** 	  | Workshop Opening
| **13:35 - 15:30** 	  | Invited talks (Chaired by Jun)
| 	  | Jat Singh, University of Cambridge. "Decision Provenance" - Accountability through data flow capture
| 	  | Michaele Veale, University College London. Fair Trade Algorithms?
| 	  | Paolo Missier, Newcastle University. Transparency and fairness of predictive models, and the provenance of data used to build them:  thoughts and challenges
| 	  | Reuben Binns, University of Oxford. Making algorithmic decision-making justifiable and contestable; some technical, legal and institutional possibilities
| 	  | Sophie Stalla-Bourdillon, University of Southampton. TBC
| **15:40 - 16:10** 	  | Coffee
| **16:10 - 17:00** 	  | Short presentations (Chaired by Reuben)                    	
| 	  | Jacqui Ayling, University of Southampton. "Algorithmic Accountability and the Role of Provenance"
| 	  | Benjamin Ujcich, University of Illinois at Urbana-Champaign. "Data Provenance for Accountability Mechanisms and Properties"
| 	  | Heather Packer, University of Southampton. "Provenance and Algorithmic Accountability in Software Engineering"
| **17:00 - 17:40** 	  | Panel Session (Chaired by Age)

### Invited speakers
* [Jat Singh](http://www.cl.cam.ac.uk/~js573/) leads the interdisciplinary Compliant and Accountable Systems research group in the Department of Computer Science and Technology, University of Cambridge. He is also a Co-I in the Microsoft Cloud Computing Research Centre (MCCRC) and co-chairs the Cambridge Trust & Technology Initiative. His research concerns the
tech-legal aspects of systems and emerging technologies, spanning areas including security, privacy, data management, and audit, typically in the context of cloud and distributed/pervasive computing environments.

  * **Talk Abstract** In discussions of algorithmic accountability, the broader context in which systems operate is often overlooked. As we see systems increasingly interconnected --- forming data-driven environments involving different technologies managed by different entities --- provenance methods show real potential for assisting accountability. To this end, this talk introduces _decision provenance_ as an area that concerns exposing the decision pipeline (the data flows and
interconnections leading up to a decision/action, as well the decision/action's cascading consequences) and indicates potential research directions for provenance techniques to assist with tackling issues of transparency, accountability, and control in complex systems environments. For more please see the paper: [Decision Provenance:
Capturing data flow for accountable systems](https://arxiv.org/abs/1804.05741).
  
* [Michael Veale](http://michae.lv) is a technology policy researcher sitting between the Department of Science, Technology, Engineering and Public Policy (STEaPP) and the Department of Computer Science at University College London. His research focuses on building new sociotechnical tools (such as methods, software and guidelines) to assess the impact of machine-learning algorithms that make societal decisions, particularly in the public sector. He has a BSc from LSE and an MSc from Maastricht University, tweets at @mikarv and can also be found at http://michae.lv . 

  * **Talk Abstract** Much has been said about how machine learning systems may create policy problems concerning fairness, accountability, privacy and power asymmetries. This talk argues that a significant omission from ethical frameworks discussed to date surrounds the provenance of these models. Given the rise in the trading or provision of trained models rather than the direct sharing of data, and the enormous disparities in privacy law around the world, this talk anticipates and analyses an emerging governance gap surrounding the social acceptability of the conditions under which the data used to train machine learning systems were obtained. This talk first asks whether European data protection law contemplates such a challenge, concluding it has few tools applicable in this context. Looking across sectors, however, this situation has surprising mirrors in sustainability standards, such as Fairtrade and Rainforest Alliance, applied to global product and commodity supply chains. Lastly, it considers the extent to which, given recent computer science research, the underlying technologies might be amenable to such governance, and if not, what might lead them to slip up.

* [Paolo Missier](https://sites.google.com/site/paolomissier/) is a Reader in Large-Scale Information Management with the School of Computing at Newcastle University, with 20+ years experience in CS research, development, and research management. The broad goal of his research is to understand the role of metadata, most notably data provenance, in making sense of the underlying (big) data as well as improving and optimising the processes that produce and extract added value from the data.
  
  * **Talk Abstract** Motivated by emerging ethical issues in Data Science, the question of ensuring Fairness and Transparency in algorithmic decision-making have recently taken centerstage in Machine Learning research, with focus on techniques for providing explanations about the behaviour of black-box predictive models. Fairness in the model is, of course, closely connected to the features used to learn the model. For instance, bias in the model can often be traced back to bias in the data. As critical decisions are encoded in data preparation workflows that affect the model's behaviour, it seems natural to want to consider details of the data processing phase when generating post hoc explanations for individual predictions. This talk will focus on the problem on ensuring transparency and understandability of the pre-processing that takes place on the data prior to it being used for learning, i.e., from acquisition and through each transformation step. In this setting, collecting the provenance of the training data seems a promising starting point, and yet it is also, surprisingly, not very well developed. I will try and offer initial thoughts for a research agenda on the role of provenance in data preparation for learning fair and explainable predictive models.

* [Reuben Binns](https://www.reubenbinns.com) is a postdoctoral researcher in Computer Science at the University of Oxford. His research interests include technical, legal and ethical aspects of privacy, machine learning, and decentralised systems. His recent research has focused on two strands: human factors of third-party tracking on the web, mobile and Internet-of-Things devices; and transparency, fairness and accountability in profiling and machine learning.

  * **Talk Abstract** Amid growing enthusiasm for automated, data-driven decision-making in the private and public sector, there is increasing concern about the potential for such 'algorithmic' systems to produce unfair and harmful outcomes. This has generated calls for 'algorithmic accountability', a term which can mean quite different things in different disciplinary contexts and amongst different stakeholders. Accountability is sometimes interpreted by technologists in terms of tractable problems and features - such as providing formal guarantees of system behaviour, or quantifying the influence of an input variable. These can be juxtaposed with social or institutional notions of accountability, e.g.: party A is accountable to party B with respect to its conduct C, if A has an obligation to provide B with some justification for C, and may face some form of sanction if B finds A’s justification to be inadequate (adapted from Bovens et al 2014). With such a definition in mind, we can reconsider which of the proposed technical solutions are likely to serve accountability in which contexts. This talk aims to provide a high-level overview of these technical and social approaches to accountability, and find points of difference and the potential mutual support between them.

* [Sophie Stalla-Bourdillon](https://www.southampton.ac.uk/law/about/staff/sophie_stalla.page) is an Associate Professor in Information Technology / Intellectual Property Law within Southampton Law School at the University of Southampton, specialising in Information Technology related issues. She is the Director of ILAWS, the Institute for Law and the Web and its interdisciplinary core iCLIC. She is a member of the Southampton Cybersecurity Centre of Excellence as well as a member of the Web Science Institute. She is the author of several legal articles, book chapters and books on intermediary liability, data protection and privacy, information security and intellectual property. 

