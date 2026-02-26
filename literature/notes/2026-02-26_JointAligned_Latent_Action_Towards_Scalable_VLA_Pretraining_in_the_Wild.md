---
title: "Joint-Aligned Latent Action: Towards Scalable VLA Pretraining in the Wild"
date: 2026-02-26
score: 35
link: https://arxiv.org/abs/2602.21736v1
pdf: https://arxiv.org/pdf/2602.21736v1.pdf
tags: ['cs.RO']
---

# 精读笔记: Joint-Aligned Latent Action: Towards Scalable VLA Pretraining in the Wild

## 🔍 WHY
(由 AI 自动生成深度分析...)

## 💡 WHAT
Despite progress, Vision-Language-Action models (VLAs) are limited by a scarcity of large-scale, diverse robot data. While human manipulation videos offer a rich alternative, existing methods are forced to choose between small, precisely-labeled datasets and vast in-the-wild footage with unreliable hand tracking labels. We present JALA, a pretraining framework that learns Jointly-Aligned Latent Actions. JALA bypasses full visual dynamic reconstruction, instead learns a predictive action embedding aligned with both inverse dynamics and real actions. This yields a transition-aware, behavior-centric latent space for learning from heterogeneous human data. We scale this approach with UniHand-Mix, a 7.5M video corpus (>2,000 hours) blending laboratory and in-the-wild footage. Experiments demonstrate that JALA generates more realistic hand motions in both controlled and unconstrained scenarios, significantly improving downstream robot manipulation performance in both simulation and real-world tasks. These results indicate that jointly-aligned latent actions offer a scalable pathway for VLA pretraining from human data.

## 🛠️ HOW
(技术细节解析...)

---
📥 PDF 直达: https://arxiv.org/pdf/2602.21736v1.pdf
