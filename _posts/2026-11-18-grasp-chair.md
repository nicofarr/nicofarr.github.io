---
title: 'Launching GRASP, a new AI research chair on interpretability of multimodal LLMs'
date: 2026-11-18
permalink: /posts/2026/grasp/
tags:
  - GRASP
  - Cluster SequoIA
  - Mechanistic interpretability
  - Graph Signal Processing
  - Multimodal LLMs
  - Structure Function coupling
---

I am very happy to announce the start of **GRASP** (*Graph Signal Processing for Interpreting and Steering Multimodal Large Language Models*), a research chair funded by the [Cluster SequoIA](https://cluster-sequoia.univ-rennes.fr/) as part of France 2030, which I hold at IMT Atlantique within the [BRAIn team](https://brain.bzh) of Lab-STICC.

**The problem.** Multimodal LLMs that take audio, images or brain signals as input sometimes ignore them: they rely on their internal linguistic priors rather than on the sensory evidence they are given. We call this failure mode *perceptual decoupling*, and it is a real obstacle to using these models in high-stakes domains such as health, neurotechnology or environmental monitoring.

**The idea.** GRASP treats a neural architecture as a communication graph and its activations as signals on that graph. Graph Signal Processing then lets us decompose internal computation into interpretable spectral components, and spectral filters become a lever for intervention. This transposes to AI models a notion I have long worked with in neuroimaging: *structure-function coupling*, i.e. how the brain's anatomical connectivity constrains its activity.

> « Neuroimaging research taught us to measure and interpret the gap between a structure and the activity flowing through it. I propose to apply the same lens to AI models. »

The chair has three objectives:

1. **A GSP framework for mechanistic interpretability**: model Transformers and state-space models as graphs, and quantify the coupling between their topology and their activation dynamics, going beyond atomised features such as those found by sparse autoencoders.
2. **Diagnosing and steering multimodal integration**: detect when a model's reasoning decouples from its sensory inputs, and introduce *filter-based steering* to re-couple it to perception, without retraining or fine-tuning.
3. **Validation on ecoacoustics and neuroimaging**: audit audio-language models for bioacoustics (Silent Cities, Observatoire de l'Environnement Nocturne, PEPR Dynabiod) and models combining video, text, audio and brain activity (Courtois NeuroMod).

**The team.** GRASP brings together [Bastien Pasdeloup](https://bastienpasdeloup.github.io/) and [Axel Marmoret](https://ax-le.github.io/) (IMT Atlantique), [Vincent Miele](https://vmiele.gitlab.io/) (CNRS, LECA) and [Jérémy Froidevaux](https://sites.google.com/view/jeremy-froidevaux/) (Université de Franche-Comté), postdoc [Venkatesh Subramani](https://venkateshness.github.io/), PhD students Nolan Sisouphanthong and Kaiteng Jiang, and collaborators Giulia Lioi (IMT Atlantique), [Lune Bellec](https://github.com/lunebellec) and [Karim Jerbi](http://www.karimjerbi.com/) (Université de Montréal, MILA).

**We are recruiting!** Several positions at the undergradutate, graduate, and postdoc positions are currently open. Feel free to get in touch if you are interested.

*This work is funded by the « Agence Nationale de la Recherche » through the France 2030 programme under the reference number ANR-23-IACL-0009.*
