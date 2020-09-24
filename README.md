# LayRareDiseases
Repository to develop layperson descriptions of rare diseases.

We start off with data developed and/or aggregated by the Monarch Initiative and Wikipedia data. The initial goal is to develop a pipeline to translate these datasets into different layperson descriptions. Further goals include serving these layperson terms for manual curation and later on, train a system to translate these terms into technical terms. This would greatly alleviate the burden of rare disease patients to describe their symptoms and condition.

## Current data
The current data includes:

| File | Description | Source | Date |
|------|-------------|--------|------|
|[HPO](data/symptoms/HP-release-20200608.json) | Human Phenotype Ontology |  | 2020-06-08 |
|[MONDO](data/diseases/MONDO-release-20200601.json) | MONDO Disease Ontology |  | 2020-06-01 |
|[Wikipedia-GPT-3](data/diseases/GPT3_medical_records.csv) | Wikipedia & GPT-3 data |  | 2020-06-01 |
