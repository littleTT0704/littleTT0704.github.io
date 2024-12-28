---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download my most recent CV [here](/files/resume.pdf) (updated: Dec. 2024).

# Education

## Carnegie Mellon University, School of Computer Science

### Master of Science in Machine Learning &#124; 2024/01 - 2024/12
* QPA: 4.16 / 4.0
* Major Courses: Advanced NLP, Probabilistic Graphical Models, Advanced CV, Deep Learning Systems

### Bachelor of Science in Artificial Intelligence &#124; 2020/09 - 2023/12
* QPA: 4.0 / 4.0
* Additional major in Psychology
* Major Courses: Algorithm Design & Analysis, Operating System, Multimodal Machine Learning, Probability Theory, Modern Regression


# Work Experience

## [Canfield Scientific](https://www.canfieldsci.com/)

### Software Development Intern &#124; 2024/05 - 2024/08
* Developed a new image editing panel using C++ and Qt, enabling users to annotate, rotate, crop, and adjust image colors efficiently.
* Collaborated with developers, UI designers, testers, and business teams to refine control logic, UI, and data management based on feedbacks.
* Presented a working prototype to the development team; delivered a final presentation to the entire company upon product update release.


## [IMC Trading](https://www.imc.com/us)

### Quant Trader Intern &#124; 2023/06 - 2023/08
* Analyzed six months of trade data to assess strategy performance during NASDAQ closing auctions; identified key factors affecting execution cost.
* Provided daily updates to mentor and weekly reports to manager; delivered a final presentation with data visualizations to enhance trading insights.


## [NoRILLA](https://www.norilla.com/)

### Software Development Intern &#124; 2022/06 - 2022/08
* Worked with UI/UX teams to develop logic and layouts for a weight-balancing game, improving gameplay and user experience.
* Optimized Java-based UI engine, isolated core functions from game logic, improved testing efficiency by 40x for faster development cycles.


## Zhengren Quantitative Investment

### Strategic Algorithm Intern &#124; 2020/12 - 2021/01
* Implemented a new strategy to reduce transaction cost; analyzed the stability of the outputs of prediction models.
* Built a back-testing system upon the data interface; gave presentations on the performance of different strategies.


# Selected Projects

### [VesselMapper](https://github.com/littleTT0704/VesselMapper) @ [GPN Lab](https://gpn.pitt.edu/) &#124; 2021/09 - 2024/02

* Developed iterative vessel segmentation using Hessian features; reduced intensity variation by 35%, improving accuracy of vessel analysis.
* Published 3 abstracts and presented at OHBM and AAIC regarding the method and statistical analysis on the features of vascular structures.
* Integrating segmentation data to train a transformer-based 3D U-Net for more robust results and faster inference.


### [TicTacTOS](https://github.com/tictactoslabs) @ [Operating Systems](https://www.cs.cmu.edu/~410/) &#124; 2023/10 - 2023/12

* Implemented a UNIX-inspired preemptive kernel on x86 architecture from scratch that provides a system call interface to the user.
* Developed a Pthreads-like thread library and a thread management interface that allows users to run multithreaded C programs.
* Collaborated with a teammate, met twice a week to update progress, coordinate tasks, solve problems and divide work; finished the project on time.


### [Self-Reflective WebArena](https://github.com/littleTT0704/webarena) @ [Advanced Natural Language Processing](https://phontron.com/class/anlp2024/) &#124; 2024/04 - 2024/05

* Improved LLM performance on WebArena subset by 10% with self-generated critiques on trajectory, enhancing long-term reasoning abilities
* Conducted ablation studies that found the ability of critic model is more effective to improve the performance of self-reflection agent.


### [Retrieval Augmented Generation System](https://github.com/littleTT0704/11711-hw2-rag) @ [Advanced Natural Language Processing](https://phontron.com/class/anlp2024/) &#124; 2024/02 - 2024/03

* Developed an end-to-end retrieval augmented generation system on information about CMU from scratch.
* Collected raw data from websites, open access papers, and plain text * documents; compiled knowledge resource by reasonable segmentation.
* Developed a complete pipeline with document retrieval with ColBERT and * generation with zero-shot and few-shot prompting T5 and Llama 2.
* Created training set with Self-Instruct pipeline; annotated validation set and evaluated validity.


### [EXCALIBUR](/publication/2023-excalibur) @ [CLAW Lab](https://talkingtorobots.com/CLAW/) &#124; 2022/09 - 2023/05

* Designed and developed a question-answer generation pipeline based on CLEVR for new question types regarding relationships between objects.
* Co-authored and published the free-form exploration benchmark *EXCALIBUR: Evaluating and Encouraging Embodied Exploration* in CVPR 2023.


### [Towards Scene-Aware ALFRED](https://github.com/hariharan98m/multimodal-alfred) @ [Multimodal Machine Learning](https://cmu-mmml.github.io/spring2023/) &#124; 2023/02 - 2023/05

* Introduced more vision-language interaction into SoTA model on ALFRED dataset; increased task success rate by 2.8% (seen) and 2.5% (unseen).
* Trained a ViLT and a BLIP to integrate the instructions into the semantic map generation module; decrease KL divergence from 0.62 to 0.59.
* Few-shot prompted GPT-4 and fine-tuned ada to improve subtask decomposition accuracy from 80% to 92%.


### Accessible Transit Information App @ [TBD Lab](https://tbd.ri.cmu.edu/) &#124; 2022/01 - 2022/05

* Developed a demo that allows users to place AR spatial anchors, mark accessible regions, and localize within accessible regions.
* Provided API to a question answering system that provides real-time navigation instructions based on localization result.


# Skills

## Programming Languages
* Proficient: Python, C++, R, C, x86 Assembly, Java
* Elementary: Swift, Standard ML

## Programming Libraries
* Python: NumPy, PyTorch, pandas, OpenCV, scikit-learn, Tensorflow, spaCy, lightgbm
* C++: Qt, Insight Toolkit (ITK), Visualization Toolkit (VTK)

## Other Tools:
* LaTeX, Git, Docker, Markdown, Unix, Vim

## Languages
* Native: Chinese, English
* Elementary: Japanese


# Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


# Teaching Experience

## Carnegie Mellon University

### [10-707: Advanced Deep Learning](https://machinelearningcmu.github.io/S24-10707/)
* Spring 2024

### [15-213: Introduction to Computer Systems](https://www.cs.cmu.edu/afs/cs/academic/class/15213-f22/www/)
* Fall 2022

### 21-127: Concepts of Mathematics
* Spring 2022, Summer 2022
