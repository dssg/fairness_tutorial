# [KDD 2023 Tutorial - Addressing Bias and Fairness in Machine Learning: A Practical Guide and Hands-on Tutorial](https://dssg.github.io/fairness_tutorial/)

Earlier versions:
* Presented at AAAI 2021 [Github repo](https://github.com/dssg/fairness_tutorial/tree/1.1), [Video](https://www.youtube.com/watch?v=HwdDQWelPy0), and [web page](https://dssg.github.io/fairness_tutorial/aaai2021.md)
* Presented at KDD 2020: [Github repo](https://github.com/dssg/fairness_tutorial/tree/1.0), [Video](https://www.youtube.com/watch?v=N67pE1AF5cM&ab_channel=DataScienceforSocialGood), and [web page](https://dssg.github.io/fairness_tutorial/kdd2020.md)

## Presenters

* [Rayid Ghani](http://www.rayidghani.com), Carnegie Mellon University
* Kit T. Rodolfa, RegLab, Stanford University
* Pedro Saleiro, Feedzai
* Sérgio Jesus, Feedzai


## Why this tutorial?

Tackling issues of bias and fairness when building and deploying machine learning and data science systems has received increased attention from the research community in recent years, yet most of the research has focused on theoretical aspects with a very limited set of application areas and data sets.  Today, we have a lack of:
1. Practical training materials
2. Methodologies to follow when building ML/data science systems that are fair and equitable for people that are affected by them
3. Tools for researchers and developers working on real-world, ML-based decision-making system to deal with issues of bias and fairness.  

Today, treating bias and fairness as primary metrics of interest, and building, selecting, and validating models using these metrics is not standard practice for data scientists. This tutorial is a step towards changing that.

## What will we cover?

In this hands-on tutorial we will bridge the gap between research and practice, by exploring fairness at the systems and outcomes level, from metrics and definitions to practical case studies, including bias audits (using the [Aequitas toolkit](http://github.com/dssg/aequitas)) and the impact of various bias reduction strategies. By the end of this hands-on tutorial, the audience will be familiar with bias audit and reduction frameworks and tools that will help them make informed design choices guided by the contexts in which their system will be deployed and used.

## Pre-Requisites
- Programming (in Python).
- Machine Learning background (understanding of and experience building ML models).
- Caring about the world, fairness, and equity.

## Schedule and Structure


[Google Slides](https://docs.google.com/presentation/d/1V3FYFlLX_L8EbQ1h5VBb0YUkWNpySNPGpUPPTR05ZSY/edit?usp=sharing) 

[Static jupyter notebooks](https://github.com/dssg/fairness_tutorial/tree/master/notebooks/)

[Interactive versions hosted on colab](https://dssg.github.io/fairness_tutorial/notebooks/) ✓

1. Overall fairness and equity when building Data Science/ML systems
    * Fairness in Systems and Outcomes
    * (Existing) Baselines
    * Sources of Bias in ML Systems
    * **Hands-on Session: Exploring Sources of Bias in Case Studies** ✓ 
        + [Case Study 1: Prioritizing after-school programs to improve high-school graduation outcomes](https://docs.google.com/document/d/1fyprl7HBMsXsXYCDyEfQL3iU8Q7lCCGtO64ixKuGPJA/edit?usp=sharing)
        + [Case Study 2: Analyzing social media data to assess damage and respond to natural disasters](https://docs.google.com/document/d/1cjzo3mhPB_Rvb5bMJqhLi4KbePMxgSXQ77M2WqdnjzQ/edit?usp=sharing)
       + [Case Study 3: Making bank loan denial decisions based on risk of not paying back in time](https://docs.google.com/document/d/16adKrjC8vLKpaoj0WeFhjMEqO1wolCZp5RldZGuQ16E/edit?usp=sharing)

2. From societal goals to fairness goals to ML fairness metrics
    * ML Fairness Metrics
    * [The Fairness Tree](http://www.datasciencepublicpolicy.org/wp-content/uploads/2021/04/Fairness-Full-Tree.png): Mapping from Societal and Fairness Goals to ML Fairness Metrics ([Zoomed in Version](http://www.datasciencepublicpolicy.org/wp-content/uploads/2021/04/Fairness-Short-Tree.png)
    * **Hands-on Session: Choosing Relevant Fairness Metric(s) in Case Studies** ✓ 
        + [Case Study 1: Prioritizing after-school programs to improve high-school graduation outcomes](https://docs.google.com/document/d/1fyprl7HBMsXsXYCDyEfQL3iU8Q7lCCGtO64ixKuGPJA/edit?usp=sharing)
        + [Case Study 2: Analyzing social media data to assess damage and respond to natural disasters](https://docs.google.com/document/d/1cjzo3mhPB_Rvb5bMJqhLi4KbePMxgSXQ77M2WqdnjzQ/edit?usp=sharing)
       + [Case Study 3: Making bank loan denial decisions based on risk of not paying back in time](https://docs.google.com/document/d/16adKrjC8vLKpaoj0WeFhjMEqO1wolCZp5RldZGuQ16E/edit?usp=sharing)
        
3. Audit bias and fairness of an ML-based decision-making system
   * Overview of [Aequitas, an open source bias and fairness audit tool](http://www.datasciencepublicpolicy.org/projects/aequitas/)
   * What is needed to audit models and predictions?
   * **Hands-on Session: [Auditing the predictions of an ML model](https://colab.research.google.com/github/dssg/fairness_tutorial/blob/master/notebooks/single_model_audit.ipynb)** ✓ 
     + [Static Python notebook on github](https://github.com/dssg/fairness_tutorial/blob/master/notebooks/single_model_audit.ipynb)
     + [Interactive Colab notebook](https://colab.research.google.com/github/dssg/fairness_tutorial/blob/master/notebooks/single_model_audit.ipynb)
    
4. Explore bias reduction strategies
    * Overview of bias reduction strategies
        + Reducing bias through 'fairness-aware' Model Selection
        + 'Fixing' the data: Sampling approaches
        + 'Fixing' the model: Regularization approaches
        + Post-hoc adjustments to improve fairness
    * Case Studies
    * **Hands-on Session: [Try bias reduction strategies](https://colab.research.google.com/github/dssg/fairness_tutorial/blob/master/notebooks/bias_reduction.ipynb)** ✓
      + 'Fixing' the data: Sampling approaches [static notebook on github](https://github.com/dssg/fairness_tutorial/blob/master/notebooks/bias_reduction.ipynb), [interactive colab version](https://colab.research.google.com/github/dssg/fairness_tutorial/blob/master/notebooks/bias_reduction.ipynb)
      + 'Fixing' the model: Regularization approaches [static notebook on github](https://github.com/dssg/fairness_tutorial/blob/master/notebooks/bias_reduction.ipynb), [interactive colab version](https://colab.research.google.com/github/dssg/fairness_tutorial/blob/master/notebooks/bias_reduction.ipynb)
      + Post-hoc adjustments to improve fairness [static notebook on github](https://github.com/dssg/fairness_tutorial/blob/master/notebooks/bias_reduction.ipynb), [interactive colab version](https://colab.research.google.com/github/dssg/fairness_tutorial/blob/master/notebooks/bias_reduction.ipynb)
      
 5. Wrap-Up
    * Things to remember
    * Additional tools and resources

## Resources
- [Aequitas](http://www.datasciencepublicpolicy.org/projects/aequitas/): Bias Audit Toolkit
- Bias and Fairness in ML [draft book chapter](https://textbook.coleridgeinitiative.org/chap-bias.html)

## References

### Bias Reduction Papers

- André Cruz, Catarina Belém, João Bravo, Pedro Saleiro, and Pedro Bizarro. FairGBM: Gradient Boosting with Fairness Constraints. 11th International Conference on Learning Representations, ICLR 2023. 

- Alekh Agarwal, Alina Beygelzimer, Miroslav Dudfk, John Langford, and Hanna Wallach. A reductions approach to fair classification. 35th International Conference on Machine Learning, ICML 2018, 1:102–119, 2018.

- Muhammad Bilal Zafar, Isabel Valera, Manuel Gomez Rodriguez, and Krishna P. Gummadi. Fairness beyond disparate treatment & disparate impact: Learning classification without disparate mistreatment. 26th International World Wide Web Conference, WWW 2017, pages 1171–1180, 2017.

- Muhammad Bilal Zafar, Isabel Valera, Manuel Gomez Rodriguez, and Krishna P. Gummadi. Fairness constraints: Mechanisms for fair classification. Proceedings of the 20th International Conference on Artificial Intelligence and Statistics, AISTATS 2017, 54, 2017.

- L. Elisa Celis, L. Huang, V. Keswani, N. K. Vishnoi, Classification with fairness constraints: a meta-algorithm with provable guarantees. Proceedings of the Conference on Fairness, Accountability, and Transparency (ACM, 2019), pp. 319–328.

- Andrew Cotter, Maya Gupta, Heinrich Jiang, Nathan Srebro, Karthik Sridharan, Serena Wang, Blake Woodworth, and Seungil You. Training Well-Generalizing
Classifiers for Fairness Metrics and Other Data-Dependent Constraints. In Proceedings of the 36th International Conference on Machine Learning, volume 97,
pages 1397–1405, Long Beach, California, USA, jun 2019. PMLR.


### Post Modeling Correction Papers
- Geoff Pleiss, Manish Raghavan, Felix Wu, Jon Kleinberg, and Kilian Q Weinberger. On Fairness and Calibration. In I Guyon, U V Luxburg, S Bengio, H Wallach,
R Fergus, S Vishwanathan, and R Garnett, editors, Advances in Neural Information Processing Systems 30, pages 5680–5689. Curran Associates, Inc., 2017.

- Moritz Hardt, Eric Price, and Nathan Srebro. Equality of Opportunity in Supervised Learning. Advances in Neural Information Processing Systems, (Nips):1–22, 2016.

- Kit T Rodolfa, Erika Salomon, Lauren Haynes, Iván Higuera Mendieta, Jamie Larson, and Rayid Ghani. Case study: predictive fairness to reduce misdemeanor
recidivism through social service interventions. In Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency, pages 142–153, 2020.


### Case Studies
- Alexandra Chouldechova, Diana Benavides-Prado, Oleksandr Fialko, and Rhema Vaithianathan. A case study of algorithm-assisted decision making in child maltreatment hotline screening decisions. In Conference on Fairness, Accountability and Transparency, pages 134–148, 2018

- Kit T Rodolfa, Erika Salomon, Lauren Haynes, Iván Higuera Mendieta, Jamie Larson, and Rayid Ghani. Case study: predictive fairness to reduce misdemeanor
recidivism through social service interventions. In Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency, pages 142–153, 2020.


## Acknowledgements

- Aaron Dunmore
- Beatriz Malveiro
- Catarina Belém
- David Polido
