---
layout: about
title: about
permalink: /
subtitle: M.Sc. Researcher, <a href="https://www.epfl.ch/" target="_blank">EPFL</a> · Lausanne, Switzerland

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p><strong>Chair of Risk Analytics &amp; Optimization</strong></p>
    <p><strong>Signal Processing Lab (LTS4)</strong></p>
    <p>EPFL, Lausanne, Switzerland</p>

news: true
latest_posts: true
selected_papers: true
social: true
---

I am a graduate researcher at **EPFL**, working at the intersection of the
[Chair of Risk Analytics and Optimization (RAO)](https://www.epfl.ch/labs/rao/) with
[Prof. Daniel Kuhn](https://people.epfl.ch/daniel.kuhn) and the
[Signal Processing Laboratory (LTS4)](https://www.epfl.ch/labs/lts4/) with
[Prof. Pascal Frossard](https://people.epfl.ch/pascal.frossard).

I am drawn to the **mathematical foundations of deep learning** — *why* neural networks
fail under adversarial perturbations and distribution shift, and what principled
algorithms follow. My work spans **adversarial robustness**, **generalization**, and
**post-training methods** (model merging, model editing) for foundation models, with
recent work on the **optimal-transport geometry** of adversarial training,
**distributionally robust optimization**, and **efficient LLM pretraining** through
optimizer-aware data selection.

I aim to derive rigorous guarantees and turn them into deployable algorithms. My
research has appeared at **NeurIPS**, **ICML**, and **ICLR**.

Before EPFL, I completed a B.Sc. in Electrical Engineering & Computer Science at
**Amirkabir University of Technology (Tehran Polytechnic)**.

---

#### Research interests

- Adversarial robustness and certified defenses
- Distributionally robust optimization & optimal transport
- LLM pretraining, optimization, and data curricula
- Model merging, model soups, and weight-space methods
- Robust fine-tuning of vision–language foundation models (CLIP)
- Linear mode connectivity and the loss landscape

#### Recent research

- **[Brenier Meets Adversarial Training](https://arxiv.org/abs/2609.31363)** — accepted
  at **NeurIPS 2026**. We use optimal-transport geometry to build structured
  adversaries for robust learning (with Ehsan Sharifian, Buse Şen, Marco Cuturi,
  and Daniel Kuhn).
- **[OptiSelect](https://arxiv.org/abs/2610.03432)** — a new preprint with **Simin Fan**
  and **Martin Jaggi** on optimizer-aware data selection and training recipes for
  efficient **LLM pretraining**.
- **MonoSoup** — a hyperparameter-free, data-free post-hoc method that recovers
  Model-Soup-level OOD accuracy from a *single* fine-tuned checkpoint, reducing
  ensembling cost from $\mathcal{O}(K)$ to $\mathcal{O}(1)$ (ICML 2026).
