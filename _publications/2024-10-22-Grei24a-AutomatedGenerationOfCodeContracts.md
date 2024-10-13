---
title: "Automated Generation of Code Contracts --- Generative AI to the Rescue?"
collection: publications
permalink: /publication/2024-10-22-Grei24a-AutomatedGenerationOfCodeContracts
excerpt: 'This paper examines the potential of Generative AI to automatically generate code contracts in terms of pre- and postconditions for any Java project without requiring any additional auxiliary artifact.'
date: 2024-10-22
paperurl: 'http://scg.unibe.ch/archive/papers/Grei24a-CodeContracts.pdf'
venue: 'GPCE 2024: Proceedings of the 23rd international conference on Generative programming and component engineering'
citation: 'Sandra Greiner and Noah Bülmann and Manuel Ohrndorf and Christos Tsigkanos and Oscar Nierstrasz and Timo Kehrer, Automated Generation of Code Contracts — Generative AI to the Rescue?, GPCE 2024: Proceedings of the 23rd international conference on Generative programming and component engineering, 2024'
---

[PDF download](http://scg.unibe.ch/archive/papers/Grei24a-CodeContracts.pdf)
| [SCG bib citation](https://scg.unibe.ch/scgbib/?query=Grei24a&filter=Year)

# Abstract

Design by Contract represents an established, lightweight paradigm for
engineering reliable and robust software systems by specifying verifiable
expectations and obligations between software components. Due to its laborious nature,
developers hardly adopt Design by Contract in practice. A plethora of research on
(semi-)automated inference to reduce the manual burden has not improved the adoption
of so-called code contracts in practice. This paper examines the potential of
Generative AI to automatically generate code contracts in terms of pre- and
postconditions for any Java project without requiring any additional auxiliary
artifact. To fine-tune two state-of-the-art Large Language Models, CodeT5 and CodeT5+,
we derive a dataset of more than 14k Java methods comprising contracts in form of Java
Modeling Language (JML) annotations, and train the models on the task of generating
contracts. We examine the syntactic and semantic validity of the contracts generated
for software projects not used in the fine-tuning and find that more than 95% of the
generated contracts are syntactically correct and exhibit remarkably high completeness
and semantic correctness. To this end, our fully automated method sets the stage for
future research and eventual broader adoption of Design by Contract in software
development practice.


