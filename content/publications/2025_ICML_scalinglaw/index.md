---
image_scale: 2.0
title: "Scaling Laws for Floating Point Quantization Training"
date: 2025-01-04
publishDate: 2025-01-04
authors: ["Xingwu Sun", "Shuaipeng Li", "Ruobing Xie", "et.al."]
# authors: ["Xingwu Sun", "Shuaipeng Li", "Ruobing Xie", "Weidong Han", "Kan Wu", "Zhen Yang", "Yixing Li", "An Wang", "Shuai Li", "Jinbao Xue", "Yu Cheng", "Yangyu Tao", "Zhanhui Kang", "Chengzhong Xu", "Di Wang", "Jie Jiang"]
publication_types: ["1"]
abstract: "Low-precision training is considered an effective strategy for reducing both training and downstream inference costs. Previous scaling laws for precision mainly focus on integer quantization, which pay less attention to the constituents in floating-point (FP) quantization, and thus cannot well fit the LLM losses in this scenario. In contrast, while FP quantization training is more commonly implemented in production, it's research has been relatively superficial. In this paper, we thoroughly explore the effects of FP quantization targets, exponent bits, mantissa bits, and the calculation granularity of the scaling factor in FP quantization training performance of LLM models. In addition to an accurate FP quantization unified scaling law, we also provide valuable suggestions for the community: (1) Exponent bits contribute slightly more to the model performance than mantissa bits. We provide the optimal exponent-mantissa bit ratio for different bit numbers, which is available for future reference by hardware manufacturers; (2) We discover the formation of the critical data size in low-precision LLM training. Too much training data exceeding the critical data size will inversely bring in degradation of LLM performance; (3) The optimal FP quantization precision is directly proportional to the computational power, but within a wide computational power range. We estimate that the best cost-performance precision should lie between 4-8 bits."
featured: true
publication: "ICML 2025"
tldr: "This paper examines floating-point quantization in LLM training, proposes a unified scaling law, and offers key recommendations for improving model performance and cost-efficiency."
links:
  - icon_pack: fas
    icon: file-pdf
    name: Link to arxiv
    url: 'https://arxiv.org/abs/2501.02423'
  - icon_pack: fas
    icon: external-link-alt
    name: Link to ICML
    url: 'https://icml.cc/virtual/2025/poster/46293'
---
