# Bayesian differential programming for robust systems identification under uncertainty

Code and data accompanying the manuscript titled "Bayesian differential programming for robust systems identification under uncertainty", authored by Y. Yang, A. Bhouri and P. Perdikaris. Will become available after the peer review process is complete.

### Abstract

This paper presents a machine learning framework for Bayesian systems identification from noisy, sparse and irregular observations of nonlinear dynamical systems. The proposed method takes advantage of recent developments in differentiable programming to propagate gradient information through ordinary differential equation solvers and perform Bayesian inference with respect to unknown model parameters using Hamiltonian Monte Carlo sampling. This allows an efficient inference of the posterior distributions over plausible models with quantified uncertainty, while the use of sparsity-promoting priors enables the discovery of interpretable and parsimonious representations for the underlying latent dynamics. A series of numerical studies is presented to demonstrate the effectiveness of the proposed methods including nonlinear oscillators, predator-prey systems and examples from systems biology. Taken all together, our  findings put forth a flexible and robust workflow for data-driven model discovery under uncertainty.

### Citation

    @article{yang2020bayesian,
      title={Bayesian differential programming for robust systems identification under uncertainty},
      author={Yang, Yibo and Bhouri, Mohamed Aziz and Perdikaris, Paris},
      journal={arXiv preprint arXiv:2004.06843},
      year={2020}
    }
