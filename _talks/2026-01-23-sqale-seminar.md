---
title: "SQALE: A large Text-to-SQL dataset with Realistic Database Schemas"
collection: talks
type: "Seminar Talk"
permalink: /talks/2026-01-23-sqale
venue: "TRL Seminar, CWI"
date: 2026-01-23
location: "Amsterdam, Netherlands"
---

[YouTube Recording](https://youtu.be/QIc_aAC7iHc)

In this talk at the TRL Seminar Series at CWI, I presented **SQALE**, a large-scale dataset aimed at advancing text-to-SQL systems through more realistic training and evaluation data.

Natural language interfaces for databases rely on text-to-SQL models to translate user questions into executable SQL queries. While recent advances in large language models have led to substantial performance improvements, progress remains constrained by the limited scale, diversity, and realism of existing benchmarks.

SQALE addresses these limitations by providing over **517,000 validated (question, schema, query) triples** grounded in **135,000+ real-world relational database schemas** derived from SchemaPile. The dataset is constructed using a principled semi-synthetic pipeline that combines schema extension, natural language question generation, SQL synthesis, and execution-based validation.

In the talk, I discussed the design criteria behind SQALE, compared its statistical properties to existing benchmarks such as Spider 2.0 and BIRD, and showed how SQALE enables more realistic training and evaluation of text-to-SQL models operating over complex, real-world database schemas.
