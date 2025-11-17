---
layout: archive
#title: "Research"
permalink: /research/
author_profile: true

---

{% include base_path %}

Working Paper
======
"Bayesian Synthetic Control with a Soft Simplex Constraint", with Quan Zhou \[JMP\]  [\[Draft\]](https://drive.google.com/file/d/1HKe4itKzJ5nimItUCmOiAGj9oeorRezM/view?usp=sharing) [\[arXiv\]](https://arxiv.org/abs/2503.06454)


<details>
<summary>Abstract</summary>

The use of the simplex constraint and challenges posed by high-dimensional data are two major concerns in the empirical application of the synthetic control method (SCM). To address both issues simultaneously, we propose a Bayesian SCM that integrates a soft simplex constraint within spike-and-slab variable selection. The hierarchical prior structure captures the extent to which the data supports the simplex constraint, allowing for more efficient and data-adaptive counterfactual estimation. The intractable marginal likelihood induced by the soft simplex constraint presents a major computational challenge, which we resolve by developing a novel  Metropolis-within-Gibbs  algorithm that updates the regression coefficients of two predictors simultaneously. Our main theoretical contribution is a high-dimensional  selection consistency result for the spike-and-slab variable selection under the simplex constraint, which significantly extends the current theory for high-dimensional Bayesian variable selection. Simulation studies demonstrate that our method performs well across diverse settings. To illustrate its practical values, we apply it to two empirical examples for estimating the effect of economic policies.

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

"Doubly Robust Estimation for Causal Inference with Nonclassical Measurement Errors"

"Robust Bayesian Learning: An Application to Penalized Splines"
