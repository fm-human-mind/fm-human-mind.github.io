---
layout: page
permalink: /
title: "Foundation Models of the Human Mind"
description: 
nav: false
nav_order: 5

---

Recent advances in foundation models have transformed how we build artificial systems capable of processing and reasoning over language and visual input, raising new opportunities for understanding the computational principles underlying human cognition. This seminar explores the emerging field of foundation models for the human mind: models that learn from large-scale behavioral or neural data to capture, predict, and characterize aspects of human perception, cognition, and brain function. We will examine the technical foundations of these models, discuss desiderata for scientifically useful models of human behavior and the brain, and critically evaluate their potential for advancing discovery in cognitive science and neuroscience.

Students will engage with recent research papers and develop individual projects that integrate foundation models with real human data, such as behavioral measurements or brain recordings, to investigate questions about representation, prediction, and mechanisms of the human mind.

**First class: Thursday, 22 October 2026, 10:00-12:00 in Building E1 5, Room 005.**


**Instructor:** [Mariya Toneva](https://mtoneva.com/)

**Teaching Assistants:** [Omer Moussa](https://ommoussa.github.io) & [Camila Kolling](https://camilakolling.github.io/)


- [Course structure](#course-structure)
  - [Requirements](#requirements)
  - [Background lectures](#background-lectures)
  - [Debates](#debates)
  - [Projects](#projects)
- [Timeline](#timeline)
- [Debate topics](#debate-topics)
  - [Debate Topic 1: Training & emergent properties](#debate-topic-1-training--emergent-properties)
  - [Debate Topic 2: Scientific use & validation](#debate-topic-2-scientific-use--validation)
- [Project ideas](#project-ideas)


## Course structure

The course consists of three main components that contribute to the final grade as follows:

- Attendance (10%)
- Debate (40%)
  - Participating in debate (20%)
  - Participating in Q&A (10%)
  - Position (10%)
- Project (50%)
  - Proposal (10%)
  - Report and code (20%)
  - Presentation (20%)

### Background lectures

We will begin the course with background lectures.
These introductory sessions aim to provide students with the technical and scientific foundations needed to understand and critically engage with research on foundation models of human behavior, cognition, and brain function.

### Debates

Some class sessions will be dedicated to debates around open questions in foundation models of the human mind.
Students will participate in debates (see the [debate topics](#debate-topics) below), prepare positions on assigned topics, and engage in discussion and Q&A.

### Projects

Students will develop an individual research project that integrates foundation models with real human data, such as behavioral measurements or brain recordings.
Projects should investigate a question related to the representation, prediction, evaluation, or scientific use of foundation models of the human mind.


## Timeline

Classes will be held in person on *Thursdays, 10:00-12:00*, in Building E1 5.

| Date | Session | Time & Location |
| :--- | :--- | :--- |
| Oct 22 | Introduction to the course | 10:00-12:00, Room 005, E1 5 |
| Oct 29 | *No class* | |
| Nov 5 | Background lecture 1 | 10:00-12:00, Room 005, E1 5 |
| Nov 12 | Background lecture 2 | 10:00-12:00, Room 005, E1 5 |
| Nov 19 | Background lecture 3 | 10:00-12:00, **Room 105**, E1 5 |
| Nov 26 | [Debate 1: Training & emergent properties](#debate-topic-1-training--emergent-properties) | 10:00-12:00, Room 005, E1 5 |
| Dec 3 | [Debate 2: Scientific use & validation](#debate-topic-2-scientific-use--validation) | 10:00-12:00, Room 005, E1 5 |
| Dec 10 | *No class* | |
| Dec 17 | Tutorial & Q&A | 10:00-12:00, Room 005, E1 5 |
| Jan 7 | Project proposals due | |
| Jan 14 | Feedback on project proposals | |
| Mar 1-15 | Final project presentations | TBA |


## Debate Topics

### Debate Topic 1: Training & emergent properties

**Brain data vs. behavioral data for training foundation models**

Should foundation models of the human mind learn from what humans do, or from what human brains do? Behavioral data provide an enormous and diverse source of supervision, while neural data offer a more direct window into the biological processes underlying cognition. This debate will compare the emergent properties of models trained primarily or exclusively on behavioral data with those trained on human brain data: What capabilities, representations, and cognitive phenomena emerge in each setting, and how do they differ? Does brain-based training lead to properties that cannot be obtained from behavioral training alone? Conversely, what aspects of human cognition are better captured by behavioral data? The debate will ultimately ask whether brain data offer unique benefits as a training signal for foundation models of the human mind, and under what circumstances those benefits justify the substantial challenges of collecting and using neural data.

**Papers**

**Brain side:**

- Ortega Caro et al. (2024). [BrainLM: A foundation model for brain activity recordings](https://proceedings.iclr.cc/paper_files/paper/2024/hash/029ce70401321de3808b3ac39e1ab167-Abstract-Conference.html). *ICLR 2024*.
- d'Ascoli et al. (2026). [A foundation model of vision, audition, and language for in-silico neuroscience](https://arxiv.org/abs/2605.04326). *arXiv:2605.04326*.
- Moussa & Toneva (2026). [RABBiT: Rapidly adaptive BOLD foundation model via brain-tuning for accurate zero-shot and few-shot prediction of speech-elicited responses in the brain](https://arxiv.org/abs/2607.05171). *NeurIPS 2026*.

**Behavior side:**

- Binz et al. (2025). [A foundation model to predict and capture human cognition](https://doi.org/10.1038/s41586-025-09215-4). *Nature*.
- Muttenthaler et al. (2025). [Aligning machine and human visual representations across abstraction levels](https://doi.org/10.1038/s41586-025-09631-6). *Nature*.
- Contier, Baker & Hebart (2024). [Distributed representations of behaviour-derived object dimensions in the human visual system](https://doi.org/10.1038/s41562-024-01980-y). *Nature Human Behaviour*.
- Binz & Schulz (2026). [A small cognitive core explains human behavior at scale](https://arxiv.org/abs/2610.13603). *arXiv:2610.13603*.


### Debate Topic 2: Scientific use & validation

**Desiderata vs. evaluation**

Should foundation models of the human mind primarily test existing theories of cognition, generate new hypotheses, or serve as benchmarks for evaluating our understanding of the mind? As computational models, they can instantiate specific hypotheses about cognitive mechanisms and test their predictions; as model organisms, they can reveal unexpected representations and mechanisms that inspire new theories. Yet neither approach guarantees scientific insight: predictive accuracy and brain alignment may not establish that a model captures the mechanisms underlying human cognition. This debate will ask what we should want from foundation models of the mind, how we should evaluate whether they achieve it, and whether current evaluation practices measure the properties that matter most. It will also consider whether discoveries made possible by these models should reshape our original scientific desiderata.

**Papers**

**Desiderata:**

- Orr et al. (2025). [Not Even Wrong: On the Limits of Prediction as Explanation in Cognitive Science](https://arxiv.org/abs/2510.03311). *arXiv:2510.03311*.
- Ying et al. (2026). [CogGym: Towards Large-Scale Comparative Evaluation of Human and Machine Cognition](https://arxiv.org/abs/2609.21259). *arXiv:2609.21259*.
- Höfling et al. (2026). [Only Brains Align with Brains: Cross-Region Alignment Patterns Expose Limits of Normative Models](https://arxiv.org/abs/2604.21780). *ICLR 2026*.
- Feather et al. (2025). [Brain-Model Evaluations Need the NeuroAI Turing Test](https://arxiv.org/abs/2502.16238). *arXiv:2502.16238*.
- Jagadish et al. (2026). [Closing the Loop to Discover Psychological Theories with an Automated Cognitive Scientist](https://arxiv.org/abs/2606.26448). *arXiv:2606.26448*.
- *Bonus:* Mineault, Griffiths & Escola (2026). [Cognitive Dark Matter: Measuring What AI Misses](https://arxiv.org/abs/2603.03414). *arXiv:2603.03414*.

**Evaluation:**

- Schrimpf et al. (2018). [Brain-Score: Which Artificial Neural Network for Object Recognition is most Brain-Like?](https://doi.org/10.1101/407007) *bioRxiv*.
- Yamins & Nayebi (2026). [Contravariance Theory: Strong Alignment for Minimal Solutions to Hard Tasks](https://arxiv.org/abs/2607.08561). *arXiv:2607.08561*.
- Schmitt et al. (2026). [A decade of comparing brains to DNNs: Progress and perspectives](https://pubmed.ncbi.nlm.nih.gov/42463327/). *Trends in Cognitive Sciences*.
- Honarmand et al. (2026). [Inducing Dyslexia in Vision Language Models](https://proceedings.iclr.cc/paper_files/paper/2026/hash/4b03821747e89ce803b2dac590f6a39b-Abstract-Conference.html). *ICLR 2026*.

