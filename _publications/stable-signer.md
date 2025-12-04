---
title: "Stable Signer: Hierarchical Sign Language Generative Model"
authors: Sen Fang*, Yalin Feng*, Hongbin Zhong, Yanxin Zhang, Dimitris N. Metaxas
collection: publications
date: 2025-12-03
venue: "arXiv 2025"
permalink: /publications/stable-signer/
pdf: https://arxiv.org/pdf/2512.04048
arxiv: https://arxiv.org/abs/2512.04048
doi: https://doi.org/10.48550/arXiv.2512.04048
citation: 'Fang, S., Feng, Y., Zhong, H., Zhang, Y., Metaxas, D. N. "Stable Signer: Hierarchical Sign Language Generative Model." arXiv:2512.04048, 2025.'
header:
  teaser: /images/SS_cover5.pdf
---
![](/images/SS_cover5.pdf)

**Abstract.**  
Sign Language Production (SLP) is the process of converting the complex input text into a real video. Most previous works focused on the Text2Gloss, Gloss2Pose, Pose2Vid stages, and some concentrated on Prompt2Gloss and Text2Avatar stages. However, this field has made slow progress due to the inaccuracy of text conversion, pose generation, and the rendering of poses into real human videos in these stages, resulting in gradually accumulating errors. Therefore, in this paper, we streamline the traditional redundant structure, simplify and optimize the task objective, and design a new sign language generative model called Stable Signer. It redefines the SLP task as a hierarchical generation end-to-end task that only includes text understanding (Prompt2Gloss, Text2Gloss) and Pose2Vid, and executes text understanding through our proposed new Sign Language Understanding Linker called SLUL, and generates hand gestures through the named SLP-MoE hand gesture rendering expert block to end-to-end generate high-quality and multi-style sign language videos. SLUL is trained using the newly developed Semantic-Aware Gloss Masking Loss (SAGM Loss). Its performance has improved by 48.6% compared to the current SOTA generation methods.

[PDF (arXiv)](https://arxiv.org/pdf/2512.04048){: .btn .btn--primary }  
[arXiv](https://arxiv.org/abs/2512.04048){: .btn }  
[DOI](https://doi.org/10.48550/arXiv.2512.04048){: .btn }