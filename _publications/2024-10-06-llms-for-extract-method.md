---
title: "Together We Go Further: LLMs and IDE Static Analysis for Extract Method Refactoring"
authors: '<i>Dorin Pomian, Abhiram Bellur, Malinda Dilhara, Zarina Kurbatova, Egor Bogomolov, Timofey Bryksin, and Danny Dig</i>'
status: "accepted"
collection: publications
permalink: /publications/2024-10-06-llms-for-extract-method
date: 2024-10-06
venue: "<b>ICSME'24</b>"
pdf: 'https://arxiv.org/abs/2401.15298'
data: 'https://llm-refactoring.github.io/'
tool: 'https://llm-refactoring.github.io/'
counter_id: 'C57'
level: 'A'
abstract: "<p><b>Abstract</b>. Excessively long methods that encapsulate multiple responsibilities within a single method are challenging to comprehend, debug, reuse, and maintain. The solution to this problem, a hallmark refactoring called Extract Method, consists of two phases: (i) choosing the statements to extract and (ii) applying the mechanics to perform this refactoring. While the application part has been a staple feature of all modern IDEs, they leave it up to developers to choose the statements to extract. Choosing which statements are profitable to extract has been the subject of many research tools that employ hard-coded rules to optimize software quality metrics. Despite steady improvements, these tools often fail to generate refactorings that align with developers' preferences and acceptance criteria. In this paper, we introduce EM-Assist, a tool that augments the refactoring capabilities of IDEs with the power of LLMs to perform Extract Method refactoring. We empirically evaluated EM-Assist on a diverse, publicly available corpus that other researchers used in the past. The results show that EM-Assist outperforms previous state-of-the-art tools: at 1% tolerance, EM-Assist suggests the correct refactoring among its top-5 suggestions 60.6% of the time, compared to 54.2% reported by existing ML models, and 52.2% reported by existing static analysis tools. When we replicated 2,849 actual Extract Method instances from open-source projects, EM-Assist's recall rate was 42.1% compared to 6.5% for its peers. Furthermore, we conducted warehouse surveys with 20 industrial developers and suggested refactorings on their recent commits. 81.3% of the respondents agreed with the recommendations provided by EM-Assist. This shows the usefulness of our approach and ushers us into a new era of refactoring when LLMs.</p>"
---