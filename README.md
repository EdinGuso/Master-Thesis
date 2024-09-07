# Master Project

Welcome to the repository for my MSc. Thesis and the accompanying presentation. This thesis was completed during my work at [Logmind](https://logmind.com/).

---

## Code Repository

The code developed as part of this project can be accessed at Logmind’s public repository: [ModuGPT Public Repository](https://bitbucket.org/ketjuni2/modugpt_public/src/main/)

---

## Abstract

This thesis explores the integration of Generative AI (GenAI) models, specifically Large Language Models (LLMs), into the field of log analytics to address the growing challenges posed by the increasing volume and complexity of log data in modern IT systems. Traditional log analysis methods, which often rely on manual inspection or rule-based approaches, struggle to keep up with the scale and variability of logs in large-scale environments. To address these limitations, this work introduces the ModuGPT framework, a modular system designed to simplify the development of LLM-powered applications for log analytics. The framework introduces Prompt Elements, a structured catalog of reusable components that streamline prompt engineering and improve the consistency and effectiveness of LLM interactions. Additionally, three specialized tools are developed within the framework: Insight-to-Text, which generates natural language explanations and recommendations for log insights; Text-to-ES, which provides a natural language interface for querying Elasticsearch; and SmartSearch, which enhances traditional search functionality by combining semantic and keyword-based methods. Evaluation results demonstrate significant improvements over baseline methods, with the Insight-to-Text tool outperforming the control in 95% of cases, Text-to-ES achieving perfect accuracy in translating natural language to Elasticsearch queries, and SmartSearch showing enhanced performance in both syntactic and semantic components of queries. The results show that integrating GenAI into log analytics workflows is important, offering a powerful new approach to understanding and managing large-scale log data and aligning with the evolving demands of AI-driven IT operations.

This thesis explores the integration of Generative AI (GenAI) models, specifically Large Language Models (LLMs), into the field of log analytics to address the growing challenges posed by the increasing volume and complexity of log data in modern IT systems. Traditional log analysis methods, which often rely on manual inspection or rule-based approaches, struggle to keep up with the scale and variability of logs in large-scale environments.

To address these limitations, this work introduces the **ModuGPT framework**, a modular system designed to simplify the development of LLM-powered applications for log analytics. The framework introduces **Prompt Elements**, a structured catalog of reusable components that streamline prompt engineering and improve the consistency and effectiveness of LLM interactions.

Additionally, three specialized tools are developed within the framework:
- **Insight-to-Text**: Generates natural language explanations and recommendations for log insights.
- **Text-to-ES**: Provides a natural language interface for querying Elasticsearch.
- **SmartSearch**: Enhances traditional search functionality by combining semantic and keyword-based methods.

Evaluation results demonstrate significant improvements over baseline methods:
- **Insight-to-Text** outperformed the control in 95% of cases.
- **Text-to-ES** achieved perfect accuracy in translating natural language to Elasticsearch queries.
- **SmartSearch** showed enhanced performance in both syntactic and semantic components of queries.

The results show that integrating GenAI into log analytics workflows is important, offering a powerful new approach to understanding and managing large-scale log data, aligning with the evolving demands of AI-driven IT operations