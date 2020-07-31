# Dealing with Bias and Fairness in Data Science Systems: A Practical Hands-on Tutorial

## Organizers

- Pedro Saleiro, Feedzai
- Kit T. Rodolfa, Carnegie Mellon University
- [Rayid Ghani](http://www.rayidghani.com), Carnegie Mellon University


## Why this tutorial?

Tackling issues of bias and fairness when building and deploying data science systems has received increased attention from the research community in recent years, yet most of the research has focused on theoretical aspects with a very limited set of application areas and data sets.  There is a lack of:
1. Practical training materials
2. Methodologies to follow when building data science systems that affect human lives
3. Tools for researchers and developers working on real-world, ML-based decision-making system to deal with issues of bias and fairness.  

Today, treating bias and fairness as primary metrics of interest, and building, selecting, and validating models using these metrics is not standard practice for data scientists. This tutorial is a step towards changing that.

## What will we cover?

In this hands-on tutorial we will bridge the gap between research and practice, by deep diving into algorithmic fairness, from metrics and definitions to practical case studies, including bias audits (using the [Aequitas toolkit](http://github.com/dssg/aequitas)) and the impact of various mitigation strategies. By the end of this hands-on tutorial, the audience will be familiar with bias audit and mitigation frameworks and tools that will help them make informed design choices guided  by the contexts in which their system will be deployed and used.

## Schedule and Structure

Part 1:  Background, core concepts and discussion
- Algorithmic decision-making and the role of data scientists.
- Legal and regulatory aspects, public vs private sector considerations.
- Understanding potential sources of bias
- Bias and Fairness definitions
- The Fairness Tree - or how to select appropriate metrics depending on actions/interventions
- Bias mitigation approaches and techniques
  - Pre-modeling
  - Model selection
  - Regularization
  - Thresholds
  - Applications
- Additional Case Studies from Social Good Projects: LA, Diabetes, Joco, El Salvador

Part 2:  Hands-on bias audit, fairness-aware model selection and case studies
- Intro to Case Study: Prioritize education crowdfunding projects for extra support that may not get funded (using DonorsChoose data)
- Define evaluation metric, protected group, and bias metrics of interest 
- Aequitas toolkit overview
- Bias Aware Modeling workflow using the Aequitas toolkit
  - Build a 'standard' model to predict risk of not getting funded
  - Audit the model for fairness
  - Build additional models
  - Audit and look at possible tradeoffs to think about bias aware model selection
  - Try other bias reduction methods
   - pre-modeling: sampling, feature selection, etc.
   - regularization
   - group specific thresholds
- Additional considerations and conclusions

Part 3: 
- Checklists
- Tools


## Pre-Requisites
- Programming (in Python).
- Machine Learning background (understanding of and experience building ML models).
- Caring about the world, fairness, and equity.

## Resources
- [Aequitas](http://www.datasciencepublicpolicy.org/projects/aequitas/): Bias Audit Toolkit
- 

