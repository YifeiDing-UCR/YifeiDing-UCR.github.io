---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

## Publications & Conference Papers

1. **Yifei Ding** and **Meng Xu**.  
   *Comparing Methods for Continuous Treatment*.  
   Presented at CODE@MIT, 2023.

2. **Haiqiang Chen**, **Yang Chen**, **Yifei Ding** and **Muqing Song**.  
   *Does "Too-Connected" Network of Shareholders Exacerbate Crash Risk?*  
   *China Economic Quarterly* (经济学季刊), 2023(03):1070-1087.  
   Available at: [Full Text](https://www.nsd.pku.edu.cn/pub/chnsd/docs/20230719150300278598.pdf)

   *Abstract:*  
   Using quarterly data from the top 10 largest shareholders of A-share stock markets from 2003 to 2018, we construct a network of influential shareholders. Our findings reveal that firms with more interconnected shareholders face higher crash risk, especially when dominated by financial institutional shareholders or those with higher shareholding ratios. In contrast, state ownership and robust corporate governance significantly mitigate this risk. Mechanism analysis shows that firms with higher network centrality tend to have a higher goodwill-to-market value ratio, a greater proportion of related-party transactions to total assets, and larger M&A premiums, yet exhibit lower corporate governance transparency. These results suggest that overly connected shareholder networks may encourage tunneling behavior, exacerbating the crash risk for listed companies.



## Working Papers

### 1. **Deep Learning for Individual Heterogeneity with Generated Regressors by Adversarial Training** (Job Market Paper)

    *Abstract:*  
    We develop a semiparametric framework that uses machine learning to capture individual heterogeneity and simultaneously estimate the control function using generated regressors. It allows us to deal with endogeneity or sample selection bias in various semiparametric models with individual heterogeneity. This framework captures individual heterogeneity through high-dimensional or highly complex observable characteristics, while the control function with generated regressors handles endogeneity and sample selection bias. Our approach involves using a well-suited deep learning framework to uncover the parameter functions and integrate the control function with generated regressors that can be easily adjusted to fit the structural configuration of the economic model. Additionally, we demonstrate Sup-norm convergence rates of the estimated parameter functions through adversarial training to adapt to the impact of generated regressors. The adversarial training estimator achieves the optimal min-max rate. These parameter functions are crucial components of the finite-dimensional structure parameters of inferential interest. We derive an influence function or orthogonal score in the context of generated regressors, which allows us to obtain valid inference that covers any second-stage parameter and any parameter functions of different ML models. An automatic differentiation engine in PyTorch allows the influence functions to be applied directly to data without any additional calculations, as in Farrell's framework. As a result, they are particularly suitable for structure parameters of inferential interest without concrete analytical forms in our framework and can be broadly applied to various structure parameters studying their individual heterogeneities.

### 2. **Estimating Partial Effects Using Machine Learning**

    *Abstract:*  
    In this paper, we explore the use of machine learning techniques for estimating partial derivatives, which is a critical step towards understanding causal relationships in econometric analysis. By leveraging modern machine learning methods, such as tree-based models and deep neural networks, we assess their effectiveness in recovering regression functions and estimating partial derivatives. We introduce a novel tree-based model, Boosting Smooth Transition Regression Trees (BooST), and compare its performance with other models, including Boosting of Symmetric Smooth Additive Regression Trees (SMARTboost) and deep neural networks (DNNs). Simulations, based on the well-known Friedman data generating process (DGP), demonstrate the superiority of BooST in estimating partial effects across various signal-to-noise environments and in the presence of redundant variables. The empirical applications, including the study of Engel curves, further highlight the ability of BooST to outperform other machine learning models in accurately estimating partial derivatives. Our findings suggest that BooST provides a powerful tool for nonparametric regression and causal inference, especially in econometric contexts where accurate estimation of marginal effects is crucial.

### 3. **A Comparative Study of Machine Learning Models for Prediction: Insights from Tree-Based Models and Deep Neural Networks**

    *Abstract:*  
    The growing influence of machine learning (ML) and big data technologies has significantly reshaped many scientific disciplines, including econometrics. This paper conducts a detailed comparative analysis of various tree-based and deep learning models, focusing on their prediction capabilities. The models examined include traditional deep neural networks (DNNs), Multilayer Perceptron (MLP), and several advanced tree-based models such as Boosted Smooth Transition Regression Trees (BooST), SMARTboost, and Random Forests. Additionally, we explore different prediction combination techniques to evaluate whether combining predictions from multiple models enhances predictive accuracy. Using simulations from the well-known Friedman data generating process (DGP), we systematically compare the performance of these models under varying levels of noise and the presence of irrelevant features. Our findings reveal that tree-based models like SMARTboost and BooST demonstrate robust performance, particularly in low signal-to-noise scenarios, where they often outperform neural networks. Moreover, the inclusion of ensemble methods, such as median and simple average combinations, further improves prediction stability. Two real-world economic applications—Engel curve prediction and stock price crash risk prediction—highlight the practical implications of our analysis, showing the advantages of tree-based methods in capturing both linear and nonlinear data structures, while DNNs struggle in noisy and nonlinear environments. Our study emphasizes the need for careful model selection and the potential benefits of hybridizing prediction models for complex data tasks.
