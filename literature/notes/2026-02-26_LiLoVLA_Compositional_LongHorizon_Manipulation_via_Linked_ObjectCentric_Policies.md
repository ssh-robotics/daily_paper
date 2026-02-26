---
title: "LiLo-VLA: Compositional Long-Horizon Manipulation via Linked Object-Centric Policies"
date: 2026-02-26
score: 33
link: https://arxiv.org/abs/2602.21531v1
pdf: https://arxiv.org/pdf/2602.21531v1.pdf
tags: ['cs.RO', 'cs.AI', 'cs.CV', 'cs.LG', 'eess.SY']
---

# 精读笔记: LiLo-VLA: Compositional Long-Horizon Manipulation via Linked Object-Centric Policies

## 🔍 WHY
(由 AI 自动生成深度分析...)

## 💡 WHAT
General-purpose robots must master long-horizon manipulation, defined as tasks involving multiple kinematic structure changes (e.g., attaching or detaching objects) in unstructured environments. While Vision-Language-Action (VLA) models offer the potential to master diverse atomic skills, they struggle with the combinatorial complexity of sequencing them and are prone to cascading failures due to environmental sensitivity. To address these challenges, we propose LiLo-VLA (Linked Local VLA), a modular framework capable of zero-shot generalization to novel long-horizon tasks without ever being trained on them. Our approach decouples transport from interaction: a Reaching Module handles global motion, while an Interaction Module employs an object-centric VLA to process isolated objects of interest, ensuring robustness against irrelevant visual features and invariance to spatial configurations. Crucially, this modularity facilitates robust failure recovery through dynamic replanning and skill reuse, effectively mitigating the cascading errors common in end-to-end approaches. We introduce a 21-task simulation benchmark consisting of two challenging suites: LIBERO-Long++ and Ultra-Long. In these simulations, LiLo-VLA achieves a 69% average success rate, outperforming Pi0.5 by 41% and OpenVLA-OFT by 67%. Furthermore, real-world evaluations across 8 long-horizon tasks demonstrate an average success rate of 85%. Project page: https://yy-gx.github.io/LiLo-VLA/.

## 🛠️ HOW
(技术细节解析...)

---
📥 PDF 直达: https://arxiv.org/pdf/2602.21531v1.pdf
