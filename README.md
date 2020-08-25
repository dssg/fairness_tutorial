# [Dealing with Bias and Fairness in Data Science Systems: A Practical Hands-on Tutorial](https://dssg.github.io/fairness_tutorial/)

## Presenters

* Pedro Saleiro, Feedzai
* Kit T. Rodolfa, Carnegie Mellon University
* [Rayid Ghani](http://www.rayidghani.com), Carnegie Mellon University


## Why this tutorial?

Tackling issues of bias and fairness when building and deploying data science systems has received increased attention from the research community in recent years, yet most of the research has focused on theoretical aspects with a very limited set of application areas and data sets.  Today, we have a lack of:
1. Practical training materials
2. Methodologies to follow when building data science systems that are fair and equitable for people that are affected by them
3. Tools for researchers and developers working on real-world, ML-based decision-making system to deal with issues of bias and fairness.  

Today, treating bias and fairness as primary metrics of interest, and building, selecting, and validating models using these metrics is not standard practice for data scientists. This tutorial is a step towards changing that.

## What will we cover?

In this hands-on tutorial we will bridge the gap between research and practice, by exploring fairness at the systems and outcomes level, from metrics and definitions to practical case studies, including bias audits (using the [Aequitas toolkit](http://github.com/dssg/aequitas)) and the impact of various bias reduction strategies. By the end of this hands-on tutorial, the audience will be familiar with bias audit and reduction frameworks and tools that will help them make informed design choices guided by the contexts in which their system will be deployed and used.

## Pre-Requisites
- Programming (in Python).
- Machine Learning background (understanding of and experience building ML models).
- Caring about the world, fairness, and equity.

## Schedule and Structure
[Google Slides](https://docs.google.com/presentation/d/146n8pyvkbZ8sS0WA3Jixb6hNGTcaD31HMuX7HRjk1rE/edit?usp=sharing) 

[PDF Slides](fairness_kdd_tutorial_slides.pdf)

[Static jupyter notebooks](https://github.com/dssg/fairness_tutorial/tree/master/notebooks/)

[Interactive versions hosted on colab](https://dssg.github.io/fairness_tutorial/notebooks/) ✓

1. Overall fairness and equity when building Data Science/ML systems
    * Fairness in Systems and Outcomes
    * (Existing) Baselines
    * Sources of Bias in ML Systems
    * **Hands-on Session: Exploring Sources of Bias in Case Studies** ✓ 
        + [Case Study 1: Making bank loan denial decisions based on risk of not paying back in time](https://docs.google.com/document/d/16adKrjC8vLKpaoj0WeFhjMEqO1wolCZp5RldZGuQ16E/edit?usp=sharing)
        + [Case Study 2: Analyzing social media data assess damage and responding to natural disasters](https://docs.google.com/document/d/1cjzo3mhPB_Rvb5bMJqhLi4KbePMxgSXQ77M2WqdnjzQ/edit?usp=sharing)
        + [Case Study 3: Prioritizing after-school programns to improve high-school graduation outcomes](https://docs.google.com/document/d/1fyprl7HBMsXsXYCDyEfQL3iU8Q7lCCGtO64ixKuGPJA/edit?usp=sharing)
        
2. From societal goals to fairness goals to ML fairness metrics
    * ML Fairness Metrics
    * [The Fairness Tree](http://www.datasciencepublicpolicy.org/wp-content/uploads/2020/02/Fairness-Weeds.png): Mapping from Societal and Fairness Goals to ML Fairness Metrics
    * **Hands-on Session: Choosing Relevant Fairness Metric(s) in Case Studies** ✓ 
        + [Case Study 1: Making bank loan denial decisions based on risk of not paying back in time](https://docs.google.com/document/d/16adKrjC8vLKpaoj0WeFhjMEqO1wolCZp5RldZGuQ16E/edit?usp=sharing)
        + [Case Study 2: Analyzing social media data assess damage and responding to natural disasters](https://docs.google.com/document/d/1cjzo3mhPB_Rvb5bMJqhLi4KbePMxgSXQ77M2WqdnjzQ/edit?usp=sharing)
        + [Case Study 3: Prioritizing after-school programns to improve high-school graduation outcomes](https://docs.google.com/document/d/1fyprl7HBMsXsXYCDyEfQL3iU8Q7lCCGtO64ixKuGPJA/edit?usp=sharing)
        
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


### Acknowledgements

- Aaron Dunmore
- Beatriz Malveiro
- Catarina Belem
- David Polido
