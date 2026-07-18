---
image_scale: 2.0
title: "Transmamba: Flexibly switching between transformer and mamba"
date: 2026-01-07
publishDate: 2026-01-07
authors: ["**Yixing Li**", "Ruobing Xie", "Zhen Yang", "Xingwu Sun", "Shuaipeng Li", "Weidong Han", "Zhanhui Kang", "Yu Cheng", "Chengzhong Xu", "Di Wang", "Jie Jiang"]
publication_types: ["1"]
abstract: "Transformers are the cornerstone of modern large language models, but their quadratic computational complexity limits efficiency in long-sequence processing. Recent advancements in Mamba, a state space model (SSM) with linear complexity, offer promising efficiency gains but suffer from unstable contextual learning and multitask generalization. Some works conduct layer-level hybrid structures that combine Transformer and Mamba layers, aiming to make full use of both advantages. This paper proposes TransMamba, a novel sequence-level hybrid framework that unifies Transformer and Mamba through shared parameter matrices (QKV and CBx), and thus could dynamically switch between attention and SSM mechanisms at different token lengths and layers. We design the Memory Converter to bridge Transformer and Mamba by converting attention outputs into SSM-compatible states, ensuring seamless information flow at TransPoints where the transformation happens. The TransPoint scheduling is also thoroughly explored for balancing effectiveness and efficiency. We conducted extensive experiments demonstrating that TransMamba achieves superior training efficiency and performance compared to single and hybrid baselines, and validated the deeper consistency between Transformer and Mamba paradigms at sequence level, offering a scalable solution for next-generation language modeling. Code and data are available at https://github.com/Yixing-Li/TransMamba"
featured: true
publication: "AAAI 2026"
tldr: "We propose TransMamba, a novel sequence-level hybrid framework that unifies Transformer and Mamba by sharing parameter matrices and memory converter. Extensive experiments demonstrates that TransMamba achieves superior training efficiency and performance compared to single and hybrid baselines." # We design the Memory Converter to bridge Transformer and Mamba by converting attention outputs into SSM-compatible states, ensuring seamless information flow at TransPoints. 
links:
  - icon_pack: fas
    icon: file-pdf
    name: Link to arxiv
    url: 'https://arxiv.org/abs/2503.24067'
  - icon_pack: fas
    icon: external-link-alt
    name: Link to AAAI
    url: 'https://ojs.aaai.org/index.php/AAAI/article/view/40451'
---
