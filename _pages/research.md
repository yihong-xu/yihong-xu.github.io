---
layout: archive
#title: "Research"
permalink: /research/
author_profile: true

---

{% include base_path %}

Working Paper
======
"Bayesian Variable Selection with A Soft Simplex Constraint: An Application to Synthetic Control Method", with Quan Zhou \[JMP\]  \[ Draft coming soon. A previous version [here](https://arxiv.org/abs/2503.06454).\]


<details>
<summary>Abstract</summary>

Whether the synthetic control method should be implemented with the simplex constraint and how to implement it in a high-dimensional setting have been widely discussed. To address both issues simultaneously, we propose a novel Bayesian synthetic control method that integrates a soft simplex constraint with spike-and-slab variable selection. Our model is featured by a hierarchical prior capturing how well the data aligns with the simplex assumption, which enables our method to efficiently adapt to the structure and information contained in the data by utilizing the constraint in a more flexible and data-driven manner. A unique computational challenge posed by our model is that conventional Markov chain Monte Carlo sampling algorithms for Bayesian variable selection are no longer applicable, since the soft simplex constraint results in an intractable marginal likelihood. To tackle this challenge, we propose to update the regression coefficients of two predictors simultaneously from their full conditional posterior distribution, which has an explicit but highly complicated characterization. This novel Gibbs updating scheme leads to an efficient Metropolis-within-Gibbs sampler that enables effective posterior sampling from our model and accurate estimation of the average treatment effect. Simulation studies demonstrate that our method performs well across a wide range of settings, in terms of both variable selection and treatment effect estimation, even when the true data-generating process does not adhere to the simplex constraint. Finally, application of our method to two empirical examples in the economic literature yields interesting insights into the impact of economic policies.

</details>

"Quantile Treatment Effects in High Dimensional Panel Data", with Li Zheng [\[arXiv\]](https://arxiv.org/abs/2504.00785) \[2nd Round R&R at *Journal of Business & Economic Statistics* (Minor Revision)\] 

<details>
<summary>Abstract</summary>

We introduce novel estimators for quantile causal effects with high dimensional panel data (large N and T), where only one or a few units are affected by the intervention or policy. Our method extends the generalized synthetic control method (Xu, 2017) from average treatment effects on the treated to quantile treatment effects on the treated, allowing the underlying factor structure to change across the quantile of the interested outcome distribution. Our method involves estimating the quantile-dependent factors using the control group, followed by a quantile regression to estimate the quantile treatment effect using the treated units. We establish the asymptotic properties of our estimators and propose a bootstrap procedure for statistical inference, supported by simulation studies. An empirical application of the 2008 China Stimulus Program is provided.



</details>

<br>


Works in Progress
======
"Super Learning: A Multiply Robust Approach in Two-Stage Semiparametric Estimation for Causal and Structural Parameters", with Li Zheng, Weiwen Yin

"Quantile Matrix Completion"

"Doubly Robust Estimation for Causal Inference with Nonclassical Measurement Errors", with Li Zheng

"Robust Bayesian Learning: An Application to Penalized Splines"
