---
title: "The Hidden Costs of Automation: An Empirical Study on GitHub Actions Workflow Maintenance"
collection: publications
permalink: /publication/2024-10-07-Vale24a-HiddenCosts
excerpt: 'This paper presents a large-scale empirical investigation towards characterizing the maintenance of GA workflows by studying the evolution of workflow files in almost 200 mature GitHub projects across ten programming languages.'
date: 2024-10-07
paperurl: 'https://arxiv.org/abs/2409.02366'
venue: 'SCAM 2024 (IEEE 24th International Working Conference on Source Code Analysis and Manipulation)'
citation: 'Pablo Valenzuela-Toledo and Alexandre Bergel and Timo Kehrer and Oscar Nierstrasz, The Hidden Costs of Automation: An Empirical Study on GitHub Actions Workflow Maintenance, Proceedings of SCAM 2024 (IEEE 24th International Working Conference on Source Code Analysis and Manipulation), 2024'
---

[PDF download](https://arxiv.org/pdf/2409.02366)
| [SCG bib citation](https://scg.unibe.ch/scgbib/?query=Vale24a&filter=Year)

# Abstract

GitHub Actions (GA) is an orchestration platform that streamlines the automatic execution of software engineering tasks such as building, testing, and deployment. Although GA workflows are the primary means for automation, according to our experience and observations, human intervention is necessary to correct defects, update dependencies, or refactor existing workflow files. In fact, previous research has shown that software artifacts similar to workflows, such as build files and bots, can introduce additional maintenance tasks in software projects. This suggests that workflow files, which are also used to automate repetitive tasks in professional software production, may generate extra workload for developers. However, the nature of such effort has not been well studied. This paper presents a large-scale empirical investigation towards characterizing the maintenance of GA workflows by studying the evolution of workflow files in almost 200 mature GitHub projects across ten programming languages. Our findings largely confirm the results of previous studies on the maintenance of similar artifacts, while also revealing GA-specific insights such as bug fixing and CI/CD improvement being among the major drivers of GA maintenance. A direct implication is that practitioners should be aware of proper resource planning and allocation for maintaining GA workflows, thus exposing the ``hidden costs of automation.'' Our findings also call for identifying and documenting best practices for such maintenance, and for enhanced tool features supporting dependency tracking and better error reporting of workflow specifications.


