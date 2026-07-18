---
image_scale: 2.0
title: "Direct preference knowledge distillation for large language models"
date: 2025-04-07
publishDate: 2025-04-07
authors: ["**Yixing Li**", "Yuxian Gu", "Li Dong", "Dequan Wang", "Yu Cheng", "Furu Wei"]
publication_types: ["3"]
abstract: "In the field of large language models (LLMs), Knowledge Distillation (KD) is a critical technique for transferring capabilities from teacher models to student models. However, existing KD methods face limitations and challenges in distillation of LLMs, including efficiency and insufficient measurement capabilities of traditional KL divergence. It is shown that LLMs can serve as an implicit reward function, which we define as a supplement to KL divergence. In this work, we propose Direct Preference Knowledge Distillation (DPKD) for LLMs. DPKD utilizes distribution divergence to represent the preference loss and implicit reward function. We re-formulate KD of LLMs into two stages: first optimizing and objective consisting of implicit reward and reverse KL divergence and then improving the preference probability of teacher outputs over student outputs. We conducted experiments and analysis on various datasets with LLM parameters ranging from 120M to 13B and demonstrate the broad applicability and effectiveness of our DPKD approach. Meanwhile, we prove the value and effectiveness of the introduced implicit reward and output preference in KD through experiments and theoretical analysis. The DPKD method outperforms the baseline method in both output response precision and exact match percentage. Code and data are available at https://aka.ms/dpkd"
featured: true
publication: "arxiv"
tldr: "We propose a novel LLMs knowledge distillation framework named direct preference knowledge distillation and demonstrate the effectiveness of preference and implicit reward in the KD process."
links:
  - icon_pack: fas
    icon: file-pdf
    name: Link to arxiv
    url: 'https://arxiv.org/abs/2406.19774'
---
