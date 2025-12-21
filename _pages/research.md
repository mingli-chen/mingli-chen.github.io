---
layout: archive
title:  " "
permalink: /research/
author_profile: true

---
 
{% if site.author.googlescholar %}
<div class="wordwrap">
You can also find my articles on  <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.
</div>
{% endif %} 

{% include base_path %}

## SELECTED PUBLICATIONS
* <a href = "https://arxiv.org/abs/1607.00286" target = "_blank"> **Quantile Graphical Models: Prediction and Conditional Independence with Applications to Systemic Risk** </a>
    * with <a href="https://people.duke.edu/~abn5/belloni-index.html?_gl=1*17po9rl*_gcl_au*MjE4MTA4MjI0LjE3MzkwNjM2MjU.*_ga*MTkxMTA3ODA4NS4xNzM5MDYzNjI1*_ga_1QY6PJLGK7*MTczOTA2MzYyNC4xLjAuMTczOTA2MzYyOC41Ni4wLjA." target="_blank">Alexandre Belloni</a> (Duke) and <a href="http://www.mit.edu/~vchern/" target="_blank">Victor Chernozhukov</a>  (MIT)
    * **Journal of Econometrics**, accepted

        <details>
        <summary>Abstract</summary>
        <p>We propose two types of Quantile Graphical Models: i) Conditional Independence Quantile Graphical Models (CIQGMs) characterize the conditional independence by evaluating the distributional dependence structure at each quantile index, as such, those can be used for validation of the graph structure in the causal graphical models; ii) Prediction Quantile Graphical Models (PQGMs) characterize the statistical dependencies through the graphs of the best linear predictors under asymmetric loss functions. PQGMs make weaker assumptions than CIQGMs as they allow for misspecification. One advantage of these models is that we can apply them to large collections of variables driven by non-Gaussian and non-separable shocks.  Because of QGMs’ ability to handle large collections of variables and focus on specific parts of the distributions, we could apply them to quantify tail interdependence. The resulting tail risk network can be used for measuring systemic risk contributions that help make inroads in understanding international financial contagion and dependence structures of returns under downside market movements.</p>


        <p>We develop estimation and inference methods focusing on the high-dimensional case, where the number of nodes in the graph is large as compared to the number of observations. For CIQGMs, these results include valid simultaneous choices of penalty functions, uniform rates of convergence, and confidence regions that are simultaneously valid. We also derive analogous results for PQGMs, which include new results for penalized quantile regressions in high-dimensional settings to handle misspecification, many controls, and a continuum of additional conditioning events. </p>
        </details>


* <a href = "https://projecteuclid.org/journals/annals-of-statistics/volume-51/issue-1/High-dimensional-latent-panel-quantile-regression-with-an-application-to/10.1214/22-AOS2223.short" target = "_blank"> **High Dimensional Latent Panel Quantile Regression with an Application to Asset Pricing** </a>
    * with <a href="https://people.duke.edu/~abn5/belloni-index.html?_gl=1*17po9rl*_gcl_au*MjE4MTA4MjI0LjE3MzkwNjM2MjU.*_ga*MTkxMTA3ODA4NS4xNzM5MDYzNjI1*_ga_1QY6PJLGK7*MTczOTA2MzYyNC4xLjAuMTczOTA2MzYyOC41Ni4wLjA." target="_blank">Alexandre Belloni</a>  (Duke University, Fuqua School of Business),  <a href="https://hernanmp.github.io" target="_blank">Oscar Hernan Madrid Padilla</a> (UCLA, Department of Statistics & Data Science), and <a href = "https://scholar.google.com/citations?user=_aNDSysAAAAJ&hl=en" target = "_blank">Kevin Wang</a> (Harvard Business School)
    * **Annals of Statistics**, Volume 51, Issue 1, Feb 2023, Pages 96-121. 

        <details>
        <summary>Abstract</summary>
        
        <p>We propose a generalization of the linear panel quantile regression model to accommodate both <em>sparse</em> and <em>dense</em> parts: sparse means while the number of covariates available is large, potentially only a much smaller number of them have a nonzero impact on each conditional quantile of the response variable; while the dense part is represented by a low-rank matrix that can be approximated by latent factors and their loadings. Such a structure poses problems for traditional sparse estimators, such as the \( \ell_1 \)-penalized Quantile Regression, and for traditional latent factor estimators, such as PCA. We propose a new estimation procedure, based on the ADMM algorithm, consisting of combining the quantile loss function with \( \ell_1 \) <em>and</em> nuclear norm regularization. We show, under general conditions, our estimator can consistently estimate both the nonzero coefficients of the covariates and the latent low-rank matrix.  </p> 
        
        
        <p>Our proposed model has a "Characteristics + Latent Factor" Asset Pricing Model interpretation: we apply our model and estimator with a large-dimensional panel of financial data and find that (i) characteristics have sparser predictive power once latent factors were controlled, and (ii) the factors and coefficients at upper and lower quantiles are different from the median.</p>
        </details>


* <a href = "https://academic.oup.com/jrsssb/article/83/5/887/7056124" target = "_blank"> **Analysis of Networks via the Sparse β-Model** </a>
    * with <a href = "https://sites.google.com/site/kkatostat/home" target = "_blank">Kengo Kato</a> (Cornell University, Department of Statistics and Data Science) and <a href = "https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/leng/" target = "_blank"> Chenlei Leng</a> (Warwick)
    * **Journal of the Royal Statistical Society, Series B**, Volume 83, Issue 5, Nov 2021, Pages 887-910.

        <details>
        <summary>Abstract</summary>
        Data in the form of networks are increasingly available in a variety of areas, yet statistical models allowing for parameter estimates with desirable statistical properties for sparse networks remain scarce. To address this, we propose the Sparse \( \beta \)-Model (S\( \beta \)M), a new network model that interpolates the celebrated Erdős–Rényi model and the \( \beta \)-model that assigns one different parameter to each node. By a novel reparameterization of the \( \beta \)-model to distinguish global and local parameters, our S\( \beta \)M can drastically reduce the dimensionality of the \( \beta \)-model by requiring some of the local parameters to be zero. We derive the asymptotic distribution of the maximum likelihood estimator of the S\( \beta \)M when the support of the parameter vector is known. When the support is unknown, we formulate a penalized likelihood approach with the \( \ell_0 \)-penalty. Remarkably, we show via a monotonicity lemma that the seemingly combinatorial computational problem due to the \( \ell_0 \)-penalty can be overcome by assigning non-zero parameters to those nodes with the largest degrees. We further show that a \( \beta\)-min condition guarantees our method to identify the true model and provide excess risk bounds for the estimated parameters. The estimation procedure enjoys good finite sample properties as shown by simulation studies. The usefulness of the S\(\beta \)M is further illustrated via the analysis of a microfinance take-up example.
        </details>


* <a href = "https://www.sciencedirect.com/science/article/pii/S0304407620301238" target = "_blank">**Nonlinear Factor Models for Network and Panel Data** </a>
    * with <a href = "https://sites.bu.edu/ivanf/" target = "_blank"> Iván Fernández-Val</a> (BU) and <a href = "https://users.ox.ac.uk/~econ0610/" target = "_blank"> Martin Weidner </a> (University of Oxford)
    * **Journal of Econometrics**, Volume 220, Issue 2, Feb 2021, Pages 296-324.

        <details>
        <summary>Abstract</summary>
        Factor structures or interactive effects are convenient devices to incorporate latent variables in panel data models. We consider fixed effect estimation of nonlinear panel single-index models with factor structures in the unobservables, which include logit, probit, ordered probit and Poisson specifications. We establish that fixed effect estimators of model parameters and average partial effects have normal distributions when the two dimensions of the panel grow large, but might suffer of incidental parameter bias. We show how models with factor structures can also be applied to capture important features of network data such as reciprocity, degree heterogeneity, homophily in latent variables and clustering. We illustrate this applicability with an empirical example to the estimation of a gravity equation of international trade between countries using a Poisson model with multiple factors.
        </details>


* **A Comparative Study of Causal Reward Design**
    * with <a href = "https://scholar.google.com/citations?user=tlhfhLoAAAAJ&hl=en" target = "_blank"> Xinlei Pan </a> (UC Berkeley)
    * Causal Machine Learning Workshop (ICML 2018)
    * Spotlight presentation


* <a href = "https://journal.r-project.org/articles/RJ-2017-033/" target = "_blank"> **Counterfactual: An R Package for Counterfactual Analysis** </a>
    * with <a href="http://www.mit.edu/~vchern/" target="_blank">Victor Chernozhukov</a>  (MIT), <a href = "https://sites.bu.edu/ivanf/" target = "_blank"> Iván Fernández-Val</a> (BU), and <a href = "https://sites.google.com/site/blaisemelly/" target = "_blank">Blaise Melly</a> (University of Bern)
    * The R Journal, Volume 9, Issue 1, June 2017, pp. 370-384


## SUBMITTED/UNDER REVISION
* <a href = "https://arxiv.org/abs/2104.09368" target = "_blank"> **Deep Reinforcement Learning in a Monetary Model** </a>
    * with <a href = "https://www.bankofengland.co.uk/research/researchers/andreas-joseph" target = "_blank"> Andreas Joseph</a> (Bank of England), <a href = "https://www.bankofengland.co.uk/research/researchers/michael-kumhof" target = "_blank"> Michael Kumhof</a> (Bank of England), <a href = "https://scholar.google.com/citations?user=tlhfhLoAAAAJ&hl=en" target = "_blank"> Xinlei Pan </a> (UC Berkeley), <a href = "https://scholar.google.com/citations?user=bRmH-2gAAAAJ&hl=en" target = "_blank">Xuan Zhou</a> (Reserve Bank of  Australia)

        <details>
        <summary>Abstract</summary>
        We study deep reinforcement learning (DRL) as a general approach to bounded rationality problems in dynamic stochastic general equilibrium models. Agents are represented by deep artificial neural networks and learn to maximize their intertemporal utility function by interacting with a model environment, of which they have no a priori knowledge. We apply our approach to a classical model from the adaptive learning literature, which looks at the interaction between monetary and fiscal policy. We find that, contrary to adaptive learning, the DRL household can solve the model, in the sense of learning the utility-maximizing steady state, in all policy regimes. However, learning may not be stable without the use of early stopping criteria. This has wider implications for the use of this class of models.
        </details>


* <a href = "https://sites.bu.edu/mrysman/files/2022/08/MM_IPP_Payments.pdf" target = "_blank" > **An MM algorithm for Fixed Eﬀects in Multinomial Models with an Application to Payment Choice in Grocery Stores** </a>
    * with <a href = "https://sites.bu.edu/mrysman/" target = "_blank"> Marc Rysman (BU)</a>, Shuang Wang (BU), <a href = "https://www.federalreserve.gov/econres/krzysztof-p-wozniak.htm" target = "_blank"> Krzysztof Wozniak </a> (Federal Reserve Board)
    * R&R, **Quantitative Economics**
       
        <details>
        <summary>Abstract</summary>
        Estimating multinomial models with many fixed effects faces prohibitive computational challenges. We develop a new method based on the Minorization-Maximization (MM) algorithm to address this issue. We provide a new proof of consistency of the MM algorithm.
        We apply our model to payment choice in grocery stores. Using rich transaction-level panel data of household purchases in a novel way, we estimate a multinomial logit discrete choice model with over 1 million fixed eﬀects. We analyze switching in the short and long-run, focusing on determinants such as transaction size and the evolution of preferences.
        </details>


* <a href = "https://warwick.ac.uk/fac/soc/economics/research/workingpapers/2016/twerp_1120_chen.pdf" target = "_blank"> **Estimation of Nonlinear Panel Models with Multiple Unobserved Effects** </a>
    * Reject &Resubmit, **Review of Economics and Statistics**
       
        <details>
        <summary>Abstract</summary>
        I propose a fixed effects expectation-maximization (EM) estimator that can be applied to a class of nonlinear panel data models with unobserved heterogeneity, which is modeled as individual effects and/or time effects. Of particular interest is the case of interactive effects, ie when the unobserved heterogeneity is modeled as a factor analytical structure. The estimator is obtained through a computationally simple, iterative two-step procedure, where the two steps have closed form solutions. I show that estimator is consistent in large panels and derive the asymptotic distribution for the case of the probit with interactive effects. I develop analytical bias corrections to deal with the incidental parameter problem. Monte Carlo experiments demonstrate that the proposed estimator has good finite-sample properties. I illustrate the use of the proposed model and estimator with an application to international trade networks.
        </details>


## REFEREE EXPERIENCE

 Journal of Econometrics (20), Journal of Business & Economic Statistics (6), Econometric Reviews, Econometric Theory (7), Statistica Sinica, Annals of Economics and Statistics, Economic Inquiry, Econometrics and Statistics, Biometrika, Journal of the American Statistical Association (4), Review of Economics and Statistics (4), Bank of England Staff Working Paper Series, Oxford Bulletin of Economics and Statistics, Annals of Statistics (2), Journal of Machine Learning Research, Journal of Applied Econometrics (2), Electronic Journal of Statistics, Review of Economic Studies (2), Journal of the Royal Statistical Society: Series B (2), Journal of Machine Learning Research, Quantitative Economics, Biometrics, Management Science 