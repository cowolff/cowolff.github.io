---
title: "Are We Asking the Right Questions? On Ambiguity in Natural Language Queries for Tabular Data Analysis"  
collection: publications  
category: conferences  
permalink: /publication/2025-12-01-gomm2025questions
excerpt: "A conceptual framework for characterising ambiguity in natural-language queries over tabular data, arguing for cooperative query specification and analysing 15 common tabular-data benchmarks."  
date: 2025-12-01  
venue: 'AI for Tabular Data Workshop @ EuRIPS 2025'  
pageurl: 'https://openreview.net/pdf?id=Mm1CGvmm9Z'  
citation: 'Gomm, D., Wolff, C., & Hulsebos, M. (2025). <i>Are We Asking the Right Questions? On Ambiguity in Natural Language Queries for Tabular Data Analysis</i>. AI for Tabular Data Workshop at EuRIPS 2025.'  
---

This paper proposes a framework to characterise natural-language queries over tabular data through the lens of cooperative interaction. Rather than treating ambiguity in user queries as a flaw, the authors argue that it often reflects users' intentional underspecification — delegating part of the interpretative burden to the system.

## Query types

The authors distinguish three types of queries:

- **Unambiguous queries** — fully specify both the analytical procedure and the data scope.
- **Cooperative queries (ambiguous but resolvable)** — contain sufficient information and allow reasonable inference so the system can derive an actionable interpretation.
- **Uncooperative queries (underspecified)** — ambiguity is irresolvable without further user input.

## Findings

Applying this framework to 15 widely used tabular-data benchmarks, the authors show that many datasets mix query types indiscriminately, which undermines reliable evaluation of models' execution accuracy and interpretation capabilities.

## Recommendations

The paper outlines implications for designing, annotating, and evaluating natural-language interfaces for tabular data analysis. Key recommendations include:

- Clearly distinguish query types when creating or annotating datasets.
- Use stratified evaluations that report performance by query type.
- Support cooperative dialog or clarification mechanisms when ambiguity cannot be resolved automatically.

