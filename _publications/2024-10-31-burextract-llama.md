---
title: "BURExtract-Llama: An LLM for Clinical Concept Extraction in Breast Ultrasound Reports"
collection: publications
category: conferences
permalink: /publication/2024-10-31-burextract-llama
excerpt: "BURExtract-Llama extracts structured clinical information from breast ultrasound reports using a Llama 3–8B model fine-tuned on GPT-4-generated annotations. It achieves an average F1 score of 84.6% on clinician-annotated reports, comparable to GPT-4, while supporting lower-cost, in-house deployment."
date: 2024-10-31
venue: "MCHM ’24: Proceedings of the 1st International Workshop on Multimedia Computing for Health and Medicine"
paperurl: "https://doi.org/10.1145/3688868.3689200"
---

**Authors:** Yuxuan Chen, Haoyan Yang, Hengkai Pan, Fardeen Siddiqui, Antonio Verdone, **Qingyang Zhang**, Sumit Chopra, Chen Zhao, and Yiqiu Shen.

Breast ultrasound reports contain clinically valuable information, but variations in language and formatting make systematic extraction challenging. We present a pipeline that uses GPT-4 to generate training annotations and fine-tunes Llama 3–8B to convert these reports into structured JSON containing 16 lesion attributes.

Evaluated against clinician annotations, BURExtract-Llama achieves an average F1 score of **84.6%**, comparable to GPT-4. This approach demonstrates how institutions can develop an in-house clinical information extraction model while reducing reliance on proprietary services and keeping inference within their own infrastructure. 

[Published Paper](https://doi.org/10.1145/3688868.3689200) | [arXiv](https://arxiv.org/abs/2408.11334)

