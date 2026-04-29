# LLMOps Pipeline for Supervised Fine-Tuning (Course Labs)

## Overview

This repository contains my hands-on lab work and code artifacts completed as part of the **LLMOps** short course by DeepLearning.AI in collaboration with Google Cloud. The repository captures an end-to-end introduction to the LLM lifecycle, from preparing instruction-tuning data to orchestrating supervised fine-tuning pipelines and evaluating model safety.

The project demonstrates practical exposure to core **LLMOps** concepts, including:

* Instruction tuning data preparation using JSONL datasets
* Data preprocessing and transformation workflows
* Pipeline orchestration using **Kubeflow Pipelines**
* Supervised fine-tuning pipeline configuration (`pipeline.yml`)
* Model and data versioning concepts
* Prompt-based inference with a deployed tuned model
* Responsible AI monitoring using safety scores for harmful content categories

## Repository Contents

```text
.
├── notebooks/
│   ├── L2_data.ipynb
│   ├── L3_automation.ipynb
│   ├── L4_predictions_prompts_safety.ipynb
├── data/
│   ├── tune_data_stack_overflow_python_qa-10_27_04_2026.jsonl
│   └── tune_eval_data_stack_overflow_python_qa-10_27_04_2026.jsonl
├── pipeline/
│   └── pipeline.yml
├── requirements.txt
└── README.md
```

## Key Concepts Demonstrated

### 1. Data Preparation for Supervised Fine-Tuning

Prepared and transformed instruction-response datasets in **JSONL** format suitable for supervised instruction tuning.

Topics explored:

* Dataset formatting for prompt-response training
* Preprocessing and transformation workflows
* Structured storage concepts using BigQuery

---

### 2. LLM Pipeline Orchestration

Configured and examined an automated tuning pipeline using **Kubeflow Pipelines**.

Included:

* Pipeline definition in YAML
* Automated workflow stages
* Experiment reproducibility concepts
* Data and model versioning practices

---

### 3. Supervised Fine-Tuning Workflow

Adapted an open-source supervised tuning pipeline for improving domain-specific question answering.

Covered:

* Tuning workflow structure
* Training configuration
* Deployment pipeline components
* Prompt-based inference testing

---

### 4. Responsible AI and Safety Monitoring

Explored safety scoring outputs to monitor harmful content risks.

Examples include:

* Safety score outputs
* Harm category filtering concepts
* Responsible AI monitoring considerations

## Tools and Technologies

* Python
* Jupyter Notebooks
* Google Cloud
* Kubeflow Pipelines
* BigQuery
* YAML
* JSONL
* Vertex AI concepts

## Learning Outcomes

Through these labs, I gained hands-on exposure to:

* Core LLMOps lifecycle components
* Differences between traditional MLOps and emerging LLMOps workflows
* Pipeline-driven fine-tuning orchestration
* Model governance and responsible AI considerations
* Multi-cloud exposure complementing my Azure MLOps background

## Notes

This repository is intended primarily as a **learning and portfolio artifact**, documenting practical implementation completed through guided labs while reinforcing concepts relevant to:

* LLM Operations (LLMOps)
* Generative AI Engineering
* MLOps / Model Lifecycle Management
* Responsible AI

## About the Course

Based on labs from the **LLMOps** short course taught by Erwin Huizenga (Developer Advocate for Generative AI on Google Cloud), offered through DeepLearning.AI.

Topics included:

* Data preparation for supervised tuning
* Automation and orchestration
* Prediction and prompt evaluation
* Safety monitoring

## Future Extensions

Possible future improvements for this repository:

* Add custom fine-tuning experiments beyond course labs
* Compare alternate orchestration frameworks
* Extend safety evaluation and guardrails
* Integrate experiment tracking tools
* Add retrieval-augmented generation (RAG) extensions

## Author

**Arlene Riona**
Data Science & AI Student | ML & Generative AI Projects
GitHub: [https://github.com/Arlene-Riona](https://github.com/Arlene-Riona)

---

If this repository was useful or interesting, feel free to star it or connect with me on LinkedIn.
