---
title: "Bridging the EHR Divide: Asymmetric Contrastive Learning for Cross-National Medical Representation Transfer"
collection: publications
category: conferences
permalink: /publication/2026-12-10-bridging-the-ehr-divide
excerpt: "This paper introduces Asymmetric SupCon, a task-specific contrastive pre-training objective for cross-national EHR representation transfer. Pre-trained on longitudinal records from 3.98 million Taiwanese NHIRD patients, the models improve over random initialization on MIMIC-IV and demonstrate strong few-shot disease-prediction performance on EHRSHOT."
date: 2026-12-10
venue: "NeurIPS 2026 GenAI4Health Workshop (Accepted, Poster)"
paperurl: "https://arxiv.org/abs/2610.04946"
---

**Author:** Qingyang Zhang
Clinical prediction tasks often have heterogeneous negative populations: patients who do not develop a particular disease may still have very different clinical histories. I introduce **Asymmetric Supervised Contrastive Learning (Asymmetric SupCon)**, a task-specific pre-training objective that brings together patient trajectories sharing a positive future outcome without explicitly attracting negative trajectories to one another.

The study pre-trains temporal Transformer encoders using a Taiwanese NHIRD cohort of **3.98 million patients**, with up to five years of history per training example, and evaluates transfer to **MIMIC-IV and EHRSHOT**. To bridge differences in clinical vocabularies, a hybrid alignment pipeline combines direct code mappings with semantic retrieval using Qwen3-Embedding-8B and FAISS.

On MIMIC-IV, NHIRD pre-training improves over random initialization across all three evaluated tasks. At EHRSHOT’s **k=16** setting, the transferred models exceed the strongest reported baseline on all five incident-disease prediction tasks, including Acute MI (**AUPRC 0.153 vs. 0.118**). A controlled ablation on approximately 400K NHIRD patients achieves the highest mean AUPRC on three of four tasks, supporting the asymmetric objective’s value for cross-national transfer.

[Paper](https://arxiv.org/abs/2610.04946) | [Code](https://github.com/qingYzhang/Asymmetric_SupCon)
