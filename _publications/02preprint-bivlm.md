---
title: "Bi-VLM: Pushing Ultra-Low Precision Post-Training Quantization Boundaries in Vision-Language Models"
collection: publications
category: manuscripts
permalink: /publication/preprint-bivlm
excerpt: 'We address the critical gap between the computational demands of vision-language models and the possible ultra-low-bit weight precision (bitwidth  bits) we can use for higher efficiency. Our work is motivated by the substantial computational cost and memory requirements of VLMs, which restrict their applicability in hardware-constrained environments. We propose Bi-VLM, which separates model weights non-uniformly based on the Gaussian quantiles. Our formulation groups the model weights into outlier (salient) and multiple inlier (unsalient) subsets, ensuring that each subset contains a proportion of weights corresponding to its quantile in the distribution. We propose a saliency-aware hybrid quantization algorithm and use it to quantize weights by imposing different constraints on the scaler and binary matrices based on the saliency metric and compression objective. We have evaluated our approach on different VLMs. For the language model part of the VLM, our Bi-VLM outperforms the SOTA by 3%-47% on the visual question answering task in terms of four different benchmarks and three different models. For the overall VLM, our Bi-VLM outperforms the SOTA by 4%-45%. We also perform token pruning on the quantized models and observe that there is redundancy of image tokens 90% - 99% in the quantized models. This helps us to further prune the visual tokens to improve efficiency.'
date: 2025-09-23
venue: 'arXiv preprint (arXiv:2509.18763)'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'http://academicpages.github.io/files/bivlm.pdf'
citation: 'Wang, X., Huang, J., Abdalla, R., Zhang, C., Xian, R., & Manocha, D. Bi-VLM: Pushing Ultra-Low Precision Post-Training Quantization Boundaries in Vision-Language Models. arXiv preprint 	arXiv:2509.18763, 2025.'
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.