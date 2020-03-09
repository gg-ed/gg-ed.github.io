---
layout: page
title: Research
description: Gar Goei's research
---

#### <u>Intraday Scheduling with Patient Re-entries and Variability in Behaviours</u>
*This paper studies the intraday patient scheduling problem, but specifically examines how to model patient re-entry, no-show, lateness and walk-ins. These features can sometimes account for around 20-40% of all patients and hence ought to be carefully considered when optimizing scheduling decisions. This paper is a sharp illustration of the P-Queue framework (the paper after this one) in action, where we observe strong numerical performance arising from the optimal scheduling policy proposed by the model.*

This paper is co-authored with Chaithanya BANDI from Kellogg, Northwestern, my student Minglong ZHOU, and a couple of medical doctors, Wilson WANG and Glen LIAU, who provided strong support in terms of practitioner experience and data. This manuscript is in Major Revision in *MSOM Special Issue on Smart City Operations*.

[The most recent version of the paper is available here.]({{ BASE_PATH}}/pages/working_papers/xray.pdf)

#### <u>Exploiting Hidden Convexity for Optimal Flow Control in Queueing Networks</u>
*This paper builds a general optimization framework (termed P-Queues) to seek a control policy in Queueing Networks that satisfies chance constraints on waiting times and other queue-based metrics. It can handle general service time distributions, general arrival distributions, non-zero initial conditions and a very large class of networks. The model appears to perform well in 36 experiments conducted on a real data set, coming within 5% of stochastic optimal and beating common heuristics by around 10%.*

This paper is co-authored with Chaithanya BANDI from Kellogg, Northwestern. This manuscript received a reject and resubmit in *Operations Research*. 

[The most recent version of the paper is available here.]({{ BASE_PATH}}/pages/working_papers/pqueue.pdf)

#### <u>Risk-based Manpower Planning: A Tractable Multi-period Model</u>

*This paper addresses the strategic workforce planning question of how many employees to maintain at each staffing level, and how to progress to this optimal structure through hiring and promotion decisions. Most notably, it incorporates time-in-grade as a factor. It introduces the idea of pipeline invariance, a technique that allows the effect of subsequent time period decisions to be retraced to the initial state, hence making the multi-period problem tractable.*

This paper is co-authored with Patrick JAILLET, from MIT, and my advisor, Melvyn SIM. It is motivated by the research I was conducting when I was still leading the team of HR analytics in the Public Service Division in Singapore. This manuscript is currently in Major Revision in *Operations Research*.

[The most recent version of the paper is available here.]({{ BASE_PATH}}/pages/working_papers/manpower.pdf)

#### <u>The Analytics of Bed Shortages: Coherent Metric, Prediction and Optimization</u>

*This paper addresses the capacity planning question in bed management. In particular, it proposes a metric that leads to a closed-form linear program. The metric allows planners to understand the effect of projected demographic shifts, as well as perform optimization on bed capacity. It is also able to handle tandem planning of capacity across different wards.*

This paper is co-authored with Jingui XIE, from USTC, my advisor, Melvyn SIM, and Shao-Wei LAM, a collaborator in a hospital. This manuscript has been submitted to *Operations Research*. It won the Best Student Paper at POMS-HK 2018.

[The most recent version of the paper is available here.]({{ BASE_PATH}}/pages/working_papers/bed_shortage.pdf)

## Working Papers and Projects

In this section, I describe some of the working papers that I have yet to turn into a manuscript format.

#### Risk-based Optimization

<b>A Robustness Framework for Resource Allocation with Both Demand and Supply Uncertainty.</b> This work examines the problem of performing an adaptive matching between demand to supply resource availability under the context of demand uncertainty and dynamic resource re-allocation. Such circumstances are common in ride-sharing networks and patient management. We build a general tractable framework and illustrate it on a maintenance work allocation setting. It is joint work with Yun Fong LIM from the Singapore Management University (SMU), and his student Peng WANG. We are expecting to make the manuscript public by May 2020. 

<b>Inventory-responsive Donor Management Policy: A Tandem Queueing Network Model.</b> In this work, we formulate a model for blood donor management as two disjoint queueing models that are to be controlled in tandem. The goal is to determine how many donors from which pools to call up for blood donation during times of shortages. We apply the technique of P-Queues to ensure that the model remains tractable. It is joint work with Sarah GAO Yini from SMU, her student Nicholas YEO, and a post-doc at the IORA, Taozeng ZHU.  

<b>Optimization of Fork-join Queues under the Pipeline Queues Paradigm.</b> The initial P-Queues framework introduced by Chaithanya and I in the first paper above, does not trivially extend to fork-join systems; this paper seeks to do just that. This is joint work with Chaithanya BANDI, Minglong ZHOU, and also Xinshang WANG at Alibaba. 

#### Interface between Machine Learning and Operations Research

<b>Decision-driven Regularization.</b> In this work, we study the setting of joint prediction and optimization problems. Specifically, we introduce a novel concept of a decision-driven regularizer, and are able to prove that our framework generalizes key models in the literature. This is joint work with my collaborator Qinshen TANG and my student Yangge XIAO. We hope to make our manuscript public by April 2020. We also intend to follow up with a more practice-based paper on the topic.

#### Other Projects

<b>Water Management and Dispatch from a Robust Perspective.</b> The control of water around a water network in the city needs to be optimized, in order to minimize flooding and meet uncertain demand. This project was completed during my stint at the Government Technology Agency in Singapore. It is joint work with my ex-colleagues, Chii Yeh CHIN and Kai Wei TAN, and Ashley NG from the Public Utilities Board. [A Medium article is written on this here.](https://medium.com/dsaid-govtech/using-robust-optimization-and-mixed-integer-programming-to-manage-singapores-water-resources-a0b899afe601)

<b>Jurong Port - Workforce Planning and Scheduling.</b> This project is a collaboration with Jurong Port. 

<!-- Note: this is how to write a comment in HTML. Everything in here won't show up on your webpage.-->

<!--
To increase the size of the title, use fewer # in front of the paper title.
To decrease the size of the title, use more #. 
To remove the italics, remove the * before and after the description
To remove the underline from the title, remove the <u> tags (<u> and </u>)
-->