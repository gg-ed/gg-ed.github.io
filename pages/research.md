---
layout: page
title: Research
description: Gar Goei's research
---



#### <u>Exploiting Hidden Convexity for Optimal Flow Control in Queueing Networks</u>
*Optimal ﬂow control in queueing networks is a challenging problem occurring in many contexts, such as data centers, cloud computing, healthcare, revenue management, and distributed networks, etc. The traditional approach has been to adopt heuristic solutions or consider inﬁnite-horizon ﬂuid or diﬀusion approximations. Motivated by emerging techniques in Robust Optimization, we propose a framework, termed Pipeline Queues, which tracks the dynamics of a queue simultaneously in terms of its queue length and waiting time. We begin by showing that the dynamics of a traditional queueing system can be modeled using our approach. Our key contribution is the uncovering of the hidden convexity resulting from our modeling approach. This leads to tractable optimization formulations that yield approximate solutions for ﬂow control problems of obtaining performance guarantees on average and quantiles of waiting time, under arbitrary arrival and service distributions with non-zero initial conditions. Our model is ﬂexible enough to capture partial observability and uncertainty of the initial state, as well as various constraints on the control policy. We apply our approach 36 diﬀerent queue networks in a real dataset at a major hospital in India, to illustrate that our proposed policies are near optimal and perform signiﬁcantly better than present heuristics.*

This manuscript has been submitted to *Operations Research*. It will also be presented at the upcoming conferences in 2019: MostlyOM, MSOM, APS and Informs Annual Meeting 2019.

[click here for the most recent version of the paper]({{ BASE_PATH}}/pages/working_papers/pqueue.pdf)

#### <u>Risk-based Manpower Planning: A Tractable Multi-period Model</u>

*The manpower planning problem of hiring and promoting has been the perennial diﬃculty of HR management. We propose a risk-based approach – ﬁnding a course of action that provides guarantees against the risk of running short of organizational targets, such as productivity, budget, headcount and managerial span of control. As such, this approach leads to an optimization model that minimizes a risk parameter, inspired by Aumann and Serrano (2008)’s riskiness index. Additionally, our model departs from the literature by considering employees’ time-in-grade, which is known to aﬀect resignations, as a decision variable. In our formulation, decisions and the uncertainty are related. To solve the model, we introduce the technique of pipeline invariance, which yields an exact re-formulation that may be tractably solved. Computational performance of the model is studied by running simulations on a real dataset of employees performing the same job function in the Singapore Civil Service. Using our model, we are able to illustrate insights into HR, such as the consequences of a lack of organizational renewal. Our model is also likely the ﬁrst numerical illustration that lends weight to a time-based progression policy common to bureaucracies. We believe that this technique of pipeline invariance could help solve a wider range of multi-period optimization problems.*

This manuscript is currently in Major Revision in *Operations Research*.

[click here for the most recent version of the paper]({{ BASE_PATH}}/pages/working_papers/manpower.pdf)

#### <u>The Analytics of Bed Shortages: Coherent Metric, Prediction and Optimization</u>

*Bed shortages in hospitals usually have a negative impact on patient satisfaction and medical outcomes. In practice, healthcare managers often use bed occupancy rates (BOR) as a metric to understand bed utilization, which is insuﬃcient in capturing the risk of bed shortages. We propose the bed shortage index (BSI) to capture more facets of bed shortage risk than traditional metrics such as the occupancy rate, the probability of shortages and expected shortages. The BSI is based on the well-known Aumann and Serrano (2008) riskiness index and it is calibrated to coincide with BOR when the daily arrivals in the hospital unit are Poisson distributed. Our metric can be tractably computed and does not require additional assumptions or approximations. As such, it can be consistently used across the descriptive, predictive and prescriptive analytical approaches. We also propose optimization models to plan for bed capacity via this metric. These models can be eﬃciently solved on a large scale via a sequence of linear optimization problems. The ﬁrst maximizes total elective throughput while managing the metric under a speciﬁed threshold. The second determines the optimal scheduling policy by lexicographically minimizing the steady-state daily BSI for a given number of scheduled admissions. We validate these models using real data from a hospital and test them against data-driven simulations. We apply these models to study the real-world problem of long stayers, to predict the impact of transferring them to community hospitals, as a result of an aging population.*

This manuscript has been submitted to *Operations Research*. It won the Best Student Paper at POMS-HK 2018.

[click here for the most recent version of the paper]({{ BASE_PATH}}/pages/working_papers/bed_shortage.pdf)

<!-- Note: this is how to write a comment in HTML. Everything in here won't show up on your webpage.-->

<!--
To increase the size of the title, use fewer # in front of the paper title.
To decrease the size of the title, use more #. 
To remove the italics, remove the * before and after the description
To remove the underline from the title, remove the <u> tags (<u> and </u>)
-->