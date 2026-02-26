---
title: "Primary-Fine Decoupling for Action Generation in Robotic Imitation"
date: 2026-02-26
score: 42
link: https://arxiv.org/abs/2602.21684v1
pdf: https://arxiv.org/pdf/2602.21684v1.pdf
tags: ['cs.RO', 'cs.LG']
---

# 精读笔记: Primary-Fine Decoupling for Action Generation in Robotic Imitation

## 🔍 WHY
(由 AI 自动生成深度分析...)

## 💡 WHAT
Multi-modal distribution in robotic manipulation action sequences poses critical challenges for imitation learning. To this end, existing approaches often model the action space as either a discrete set of tokens or a continuous, latent-variable distribution. However, both approaches present trade-offs: some methods discretize actions into tokens and therefore lose fine-grained action variations, while others generate continuous actions in a single stage tend to produce unstable mode transitions. To address these limitations, we propose Primary-Fine Decoupling for Action Generation (PF-DAG), a two-stage framework that decouples coarse action consistency from fine-grained variations. First, we compress action chunks into a small set of discrete modes, enabling a lightweight policy to select consistent coarse modes and avoid mode bouncing. Second, a mode conditioned MeanFlow policy is learned to generate high-fidelity continuous actions. Theoretically, we prove PF-DAG's two-stage design achieves a strictly lower MSE bound than single-stage generative policies. Empirically, PF-DAG outperforms state-of-the-art baselines across 56 tasks from Adroit, DexArt, and MetaWorld benchmarks. It further generalizes to real-world tactile dexterous manipulation tasks. Our work demonstrates that explicit mode-level decoupling enables both robust multi-modal modeling and reactive closed-loop control for robotic manipulation.

## 🛠️ HOW
(技术细节解析...)

---
📥 PDF 直达: https://arxiv.org/pdf/2602.21684v1.pdf
