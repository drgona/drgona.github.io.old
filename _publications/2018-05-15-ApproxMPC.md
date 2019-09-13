---
title: "Approximate model predictive building control via machine learning"
collection: publications
permalink: /publication/2018-05-15-ApproxMPC
date: 2018-05-15
venue: 'Applied Energy'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0306261918302903'
citation: '@article{DRGONA2018199,
title = "Approximate model predictive building control via machine learning",
journal = "Applied Energy",
volume = "218",
pages = "199 - 216",
year = "2018",
issn = "0306-2619",
doi = "https://doi.org/10.1016/j.apenergy.2018.02.156",
url = "http://www.sciencedirect.com/science/article/pii/S0306261918302903",
author = "Ján Drgoňa and Damien Picard and Michal Kvasnica and Lieve Helsen",
}'
---
Many studies have proven that the building sector can significantly benefit from replacing the current practice rule-based controllers (RBC) by more advanced control strategies like model predictive control (MPC). However, the optimization-based control algorithms, like MPC, impose increasing hardware and software requirements, together with more complicated error handling capabilities required from the commissioning staff. In recent years, several studies introduced promising remedy for these problems by using machine learning algorithms. The idea is based on devising simplified control laws learned from MPC. The main advantage of the proposed methods stems from their easy implementation even on low-level hardware. However, most of the reported studies were dealing only with problems with a limited complexity of the parametric space, and devising laws only for a single control variable, which inevitably limits their applicability to more complex building control problems. In this paper, we introduce a versatile framework for synthesis of simple, yet well-performing control strategies that mimic the behavior of optimization-based controllers, also for large scale multiple-input-multiple-output (MIMO) control problems which are common in the building sector. The approach employs multivariate regression and dimensionality reduction algorithms. Particularly, deep time delay neural networks (TDNN) and regression trees (RT) are used to derive the dependency of multiple real-valued control inputs on parameters. The complexity of the problem, as well as implementation cost, are further reduced by selecting the most significant features from the set of parameters. This reduction is based on straightforward manual selection, principal component analysis (PCA) and dynamic analysis of the building model. The approach is demonstrated on a case study employing temperature control in a six-zone building, described by a linear model with 286 states and 42 disturbances, resulting in an MPC problem with more than thousand of parameters. The results show that simplified control laws retain most of the performance of the complex MPC, while significantly decreasing the complexity and implementation cost.
