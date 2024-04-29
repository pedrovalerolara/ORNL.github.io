---
layout: default
title: ORNL's Secure, Trustworthy, and Energy-Efficient AI for Science Tutorial Series <br/> 
description: Organized by ORNL’s AI Initiative <br/>
             Virtual<br/>
permalink: /events/ai-tutorials-series-2024/
tags: events
---

![banner](images/FY24_AI_tutorial_seminar.png)

# ORNL AI Initiative: Secure, Trustworthy, and Energy-Efficient AI for Science Tutorial Series

ORNL [AI Initiative](https://www.ornl.gov/ai-initiative)’s tutorial series is designed to equip the scientific community with cutting-edge methodologies, technologies developed within ORNL and specifically through the AI initiative.

Each half-day tutorial is structured to cover a broad spectrum of **AI for science** applications, from graph neural networks in materials modeling to machine learning in hyperspectral image reconstruction.

The tutorials are designed for researchers of all levels who seek to deepen their understanding of AI for Science.
Our primary audience includes researchers with a foundation in AI, aiming to explore and implement advanced, trustworthy AI techniques within scientific contexts.
Additionally, we invite researchers and practitioners from the industry, as well as graduate, postgraduate, and undergraduate students from universities who are engaged in AI research and aspire to acquire knowledge specifically in AI for science.
Although we will touch upon fundamental concepts in AI for science, our curriculum does not encompass introductory AI topics.

The tutorials will place a strong emphasis on open-source principles and non-sensitive topics and content.
We will share open-source code, provide detailed code walkthroughs, and offer hands-on exercises to enhance learning and engagement.

The tutorials will be held **virtually**, allowing participants to join virtually.
Microsoft Teams link will be announced.

Registration is not required for ORNL participants.
For non-ORNL participants, an entry pass is required even for virtual attendance.
For non-US citizens, this process may take up to **45** days.
Please email Jessica Woods at woodsjb@ornl.gov **and** Taylor Bullock at bullocktm@ornl.gov. 
Include a short bio and explain why you wish to attend the tutorial series.
Note that the tutorials will be recorded and made available online after 2-3 weeks.
Therefore, please request an entry pass only if you need to attend virtually.

<a href="#top"> &#10558; Back to top</a>

# Next Tutorial

**Inverse molecular design workflow**
<br>Time: 05/24/2024, 2:00 PM - 4:00 PM (ET)
<br> Virtual (Microsoft Teams)
<br>[Pilsun Yoo](https://www.ornl.gov/staff-profile/pilsun-yoo)
<br>Oak Ridge National Laboratory

|         |
| ------- |
| [![PY](https://www.ornl.gov/sites/default/files/styles/staff_profile_image_style/public/2022-09/IMG_3034_0.jpg?h=af089f55&itok=P7E4sW5_)](https://www.ornl.gov/staff-profile/pilsun-yoo)|

**Abstract**

TBA

**Bio**

Pilsun Yoo is a Postdoctoral Research Associate in the Computational Chemistry and Nanomaterials Sciences Group in the Advanced Computing Methods for Physical Sciences Section of the Computational Sciences and Engineering Division at Oak Ridge National Laboratory (ORNL).


# Past Tutorial

**Material Property Prediction with Large Scale GNNs**
<br>Time: 03/28/2024, 2:00 PM - 4:00 PM (ET)
<br> Virtual (Microsoft Teams)
<br>[Massimiliano Lupo Pasini](https://www.ornl.gov/staff-profile/massimiliano-lupo-pasini)
<br>Oak Ridge National Laboratory

|         |
| ------- |
| [![MLP](https://www.ornl.gov/sites/default/files/styles/staff_profile_image_style/public/2019-11/MaxPortrait.jpg?h=e67f39ca&itok=0HIXThn1)](https://www.ornl.gov/staff-profile/massimiliano-lupo-pasini)|
| Massimiliano Lupo Pasini<br> Staff Scientist<br>Computing and Computational Sciences Directorate, ORNL |


**Abstract**

During the tutorial, we will show how to use HydraGNN (https://github.com/ORNL/HydraGNN), our scalable implementation of multi-task learning graph neural networks developed at Oak Ridge National Laboratory #ORNL as part of the ORNL Artificial Intelligence Initiative.
After discussing scientific motivations behind the need to develop scalable GNN training to support scientific applications of interest to the US Department of Energy (DOE), we will cover a hands-on session with examples of increasing difficulty. In particular, we will show how HydraGNN can be used to scale the training of GNN models on millions of atomic structures on OLCF-Summit, NERSC-Perlmutter, and OLCF-Frontier. To this day, we achieved linear scaling on these DOE leadership class supercomputing facilities using up to 1,024 GPUs.

**Bio**

Massimiliano (Max) Lupo Pasini obtained his Bachelor of Science and Master of Science in Mathematical Engineering at the Politecnico di Milano in Milan, Italy. The focus of his undergraduate and master studies was statistics and discretization techniques and reduction order models for partial differential equations. He obtained his PhD in Applied Mathematics at Emory University in Atlanta (GA) in May 2018. The main topic of his doctorate work was the development of efficient and resilient linear solvers for upcoming computing architectures moving towards exascale. Upon graduation, Max joined the Oak Ridge National Laboratory (ORNL) as a Postdoctoral Researcher Associate in the Scientific Computing Group at the National Center for Computational Sciences (NCCS).

In November 2019, Max became a computational scientist in the Scalable Algorithms and Coupled Physics Group in the Advanced Computing Methods for Engineered Systems Section of the Computational Sciences and Engineering Division at ORNL. In November 2020, Max became a data scientist in the Computational Coupled Physics group within the same section.

Max’s research focuses on the development of surrogate and generative AI models for material sciences, scalable hyper parameter optimization techniques for deep learning (DL) models, and acceleration of computational methods for physics applications. He was the technical lead of the Surrogates Models for Material Properties product within the Artificial Intelligence for Science and Discovery (AISD) thrust of the ORNL Artificial Intelligence Initiative in the fiscal years FY21, FY22, and FY23. He is currently the interim technical lead of the AISD thrust for fiscal years FY24 and FY25.

> [slides](https://www.dropbox.com/scl/fi/db5nw096d6y2s20mvrgu0/HydraGNN_AI_Tutorial_Series_03282024.pdf?rlkey=juiz1da3bnuld62jancqecdi5&dl=0)

<a href="#top"> &#10558; Back to top</a>

**ExpM+NF: Are normalizing flows the key to unlocking the exponential mechanism? Our efforts to advance differentially private machine learning**
<br>Time: 04/25/2024, 2:00 PM - 4:00 PM (ET)
<br> Hybrid (4100, J302; Microsoft Teams)
<br>[Robert A Bridges](https://www.ornl.gov/staff-profile/robert-bridges)
<br>Oak Ridge National Laboratory

|         |
| ------- |
| [![RAB](https://www.ornl.gov/sites/default/files/styles/staff_profile_image_style/public/profile-pic.jpg?itok=ZSphOYck)](https://www.ornl.gov/staff-profile/robert-bridges)|
| Robert A Bridges<br> Research Scientist<br>Computing and Computational Sciences Directorate, ORNL |

**Abstract**

Training machine learning models on data with privacy concerns is an increasingly common and needed situation.
Differential privacy provides a mathematical framework for rigorously guaranteeing privacy while releasing information—roughly speaking, one makes a deterministic algorithm into a randomized algorithm (e.g., by adding noise to the output) in such a way that it masks the original data.
Of course, accuracy is sacrificed for the gain of privacy.
Unfortunately, the state of the art in differentially private stochastic gradient descent (DPSGD), which is the state of the art for private machine learning, is inadequate in practice as it leads to insufficient accuracy-privacy tradeoffs.
How can we transform this field to produces sufficiently accurate models while simultaneously protecting our privacy?
This talk presents our work to explore a new approach to differentially private machine learning.  
 
First necessary background will be given.
I’ll provide an introduction to differential privacy requiring no background in the field with a focus on differentially private machine learning.
Our target is understanding the state of the art, DPSGD.
The second portion of background material will introduce normalizing flows models—a family of deep learning neural networks that, by design, preserve probability densities, and hence can be used to approximate intractable probability densities.
Basic understanding of supervised machine learning and neural networks is required.
 
Once equipped with the needed background, I’ll present our new approach, ExpM+NF.
This exploratory project investigates if we can use the Exponential Mechanism—a differential privacy mechanism for optimization—to train machine learning models with privacy.
Historically, the exponential mechanism has been sidelined as it requires sampling from an intractable distribution.
Can normalizing flow models, deep neural networks designed for handling intractable distributions be the key?
Our year 1 work seeks to answer the question "Can we train a model by sampling from the exponential mechanism via an auxiliary normalizing flow?".
Experiments and results will be presented. Our current (year 2) work seeks to prove a differential privacy guarantee that incorporates the normalizing flow's approximation to the "real" exponential mechanism distribution.

**Bio**

Robert A. Bridges (Bobby), is a Senior Research Mathematician at ORNL sitting in the National Security Sciences Directorate.
Bobby currently focuses on advancing differentially private machine learning (as this talk may suggest), and using mathematical system models to identify feedback vulnerabilities.
Bobby holds an undergraduate degree from Creighton University in mathematics as well as a PhD in mathematics from Purdue University (and he is very happy with both teams’ deep run in the March Madness tourney!)
Leaving pure mathematics, Bobby was fortunate to obtain a postdoc position at ORNL in 2012, where he has since supported a wide variety of projects with machine learning, statistical, and applied math expertise.
Previous work includes leading projects on intra-vehicle network security and reverse engineering algorithms, leading large-scale experiments testing commercial security tools, and serving for 2 years as the Cybersecurity Research Group Leader.

# Schedule 

Please reach out if you are interested in presenting at a future event

| Date | Title | ORNL Tutorial Lead |
| ---- | ----- | ------------------ |
| 03/28/2024 | Material Property Prediction with Large Scale GNNs | [Massimiliano Lupo Pasini](https://www.ornl.gov/staff-profile/massimiliano-lupo-pasini) |
| 04/25/2024 | ExpM+NF: Are normalizing flows the key to unlocking the exponential mechanism? Our efforts to advance differentially private machine learning | [Robert A Bridges](https://www.ornl.gov/staff-profile/robert-bridges) |
| 05/24/2024 | Inverse molecular design workflow | [Pilsun Yoo](https://www.ornl.gov/staff-profile/pilsun-yoo) |
| 06/28/2024 | PI3NN: Uncertainty Quantification for ML models | [Dan Lu](https://www.ornl.gov/staff-profile/dan-lu) |
| 07/26/2024 | VAE-NCDE: a generative time series model for probabilistic multivariate time series forecasting | [William L Gurecky](https://www.ornl.gov/staff-profile/william-l-gurecky) |
| 08/23/2024 | ML-HSIR: Machine Learning based Hyperspectral Image Reconstruction the edge | [Narasinga Rao Miniskar](https://www.ornl.gov/staff-profile/narasinga-r-miniskar) |
| 09/27/2024 | Massively parallel training for large transformers | [Xiao Wang](https://www.ornl.gov/staff-profile/xiao-wang) |
| 10/04/2024 | PPSD: Privacy preservation for streaming data | [Olivera Kotevska](https://www.ornl.gov/staff-profile/olivera-kotevska) |
| 11/15/2024 | Intro to causal and explainable models in materials science | [Ayana Ghosh](https://www.ornl.gov/staff-profile/ayana-ghosh) |



<a href="#top"> &#10558; Back to top</a>


# Organization

For questions, please contact us.
<style>
td, th {
   border: none!important;
}
</style>

|                |                |                |
| -------------- | -------------- | -------------- |
| [![Jong Youl Choi](https://www.ornl.gov/sites/default/files/styles/staff_profile_image_style/public/2021-02/jychoi2_0.png?h=273942d0&itok=wF9lLEZU)](https://www.ornl.gov/staff-profile/jong-youl-choi) | [![Chen Zhang](https://www.ornl.gov/sites/default/files/styles/staff_profile_image_style/public/2020-10/profile_0.png?h=c49a1206&itok=ntQg6NeU)](https://www.ornl.gov/staff-profile/chen-zhang) | [![Prasanna Balaprakash](https://www.ornl.gov/sites/default/files/styles/staff_profile_image_style/public/2023-03/BalaprakashProfile_0.jpg?h=17644140&itok=AYUSlKCG)](https://www.ornl.gov/staff-profile/prasanna-balaprakash) |
| Jong Youl Choi <br> HPC Data Research Scientist <br> Computer Science and Mathematics Division <br> ONRL | Chen Zhang <br> Computational Scientist <br> Computer Science and Mathematics Division <br> ONRL | Prasanna Balaprakash<br> Director of AI Programs <br> Distinguished R&D Staff Scientist<br> Computing and Computational Sciences Directorate, ORNL |

<a href="#top"> &#10558; Back to top</a>
