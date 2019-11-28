# Causal Inference in Data Science
__A computational introduction to causality and counterfactual reasoning with Python__

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hopelessoptimism/causality-for-the-uninitiated/master)

This repository contains the exercises and data for the [Causal Inference in Data Science Live Training](https://learning.oreilly.com/live-training/courses/causal-inference-in-data-science/0636920327097/). This training provides an invaluable, hands-on guide to applying causal inference in the wild to solve real-world data science tasks. Using an end-to-end example, we will walk through the process of posing a causal hypothesis, modeling our beliefs with causal graphs, estimating causal effects with the doWhy library in Python, and finally evaluating the soundness of our results. Rather than taking an abstract and mathematical approach to these steps, the focus of this training will be on accessible computational methods to practically answer causal questions in the context of a data science workflow.

And/or please do not hesitate to reach out to me directly via email at jondinu@gmail.com or over twitter @jonathandinu

> If you find any errors in the code or materials, please open a Github [issue](https://github.com/hopelessoptimism/causality-for-the-uninitiated/issues) in this repository

## What you'll learn-and how you can apply it
* Understand how to reason causally and why it is necessary for modern data science.
* Use the doWhy library to build, estimate, and evaluate causal models.
* Learn how to practically apply causal inference to real-world data science problems.

## This training course is for you because...
* You have taken an introductory data science course or statistics course but want to take the next step to understand the foundations of causal inference and how to effectively apply the theory to real-world problems.
* You have heard about the power of causal reasoning, but do not know how to get started learning its basics or applying it to your own problems.
* You are an aspiring data scientist looking to break into the field and need to learn the practical skills necessary for what you will encounter on the job.
* You are a quantitative researcher interested in applying theory to real projects by taking a computational approach to causal inference.
* You are a software engineer interested in leveraging analytics to augment your application development process.

## Prerequisites

* Experience with an object-oriented programming language, e.g., Python (all code demos during the training will be in Python)
* Familiarity with basic probability and statistics (e.g. distributions and hypothesis testing).
* A working knowledge of the scientific Python libraries (numpy, pandas and scikit-learn) is helpful but not required.

## Course Set-up

Download the appropriate Python 3.7 Anaconda Distribution for your operating system: https://www.anaconda.com/distribution/

## Recommended Preparation

* Data Science Fundamentals Part 2: Machine Learning and Statistical Analysis (Lesson 7 and 8) ](https://learning.oreilly.com/videos/data-science-fundamentals/9780134778877)

## Data

* `notebooks/data`
* [Inside Airbnb](http://insideairbnb.com/get-the-data.html)

## Schedule/Outline

_The time frames are only estimates and may vary according to how the class is progressing_

### Identifying Causal Effects (50min)

* Randomized Control Trials
* Counterfactuals and Potential Outcomes
* Causal Graphical Models

### Estimating Causal Effects (50min)

* Propensity Score Matching
* Instrument Variables
* Causal Effect Inference with Machine Learning

**Break 10 min**

### Evaluating Causal Models (30min)

* Random Confounders and Placebos
* Cross Validation
* Sensitivity Analysis

### Discovering Causal Structure (25min)

* Guess and Test
* Automated Graph Discovery
* Q&A

## Resources

### Books

* [Elements of Causal Inference](https://mitpress.mit.edu/books/elements-causal-inference)
* [Causal Inference: What If](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)
* [Causal Inference for Statistics, Social, and Biomedical Sciences](https://www.cambridge.org/core/books/causal-inference-for-statistics-social-and-biomedical-sciences/71126BE90C58F1A431FE9B2DD07938AB)
* [Counterfactuals and Causal Inference Methods and Principles for Social Research](https://www.cambridge.org/core/books/counterfactuals-and-causal-inference/5CC81E6DF63C5E5A8B88F79D45E1D1B7)
* [Advanced Data Analysis from an Elementary Point of View](https://www.stat.cmu.edu/~cshalizi/ADAfaEPoV/)
    * Chapter 18: Graphical Models
    * Chapter 19: Graphical Causal Models
    * Chapter 20: Identifying Causal Effects from Observations
    * Chapter 21: Estimating Causal Effects from Observations
    * Chapter 22: Discovering Causal Structure from Observations
* [Causality: Models, Reasoning, and Inference](http://bayes.cs.ucla.edu/BOOK-2K/)

### Courses

* [Applied Causality (Columbia)](http://www.cs.columbia.edu/~blei/seminar/2019-applied-causality/index.html)
* [Intermediate Statistics (CMU): Causal Inference](http://www.stat.cmu.edu/~larry/=stat705/Lecture17.pdf)
* [Causal Inference and Learning (UIC)](https://www.cs.uic.edu/~elena/courses/fall19/cs594cil.html)
* [KDD Tutorial on Causal Inference and Counterfactual Reasoning](https://causalinference.gitlab.io/kdd-tutorial/)

### References

* [Causality for Machine Learning](https://arxiv.org/abs/1911.10500v1)
* [Fairness and Machine Learning: Chapter 4](https://fairmlbook.org/causal.html)
* [Causal Inference Animated Plots](http://nickchk.com/causalgraphs.html)
* [Causal Data Science blog posts](https://medium.com/causal-data-science/causal-data-science-721ed63a4027)
* [Causal inference in statistics: An overview](https://ftp.cs.ucla.edu/pub/stat_ser/r350.pdf)
* [The Statistics of Causal Inference: A View from Political Methodology](http://lukekeele.com/wp-content/uploads/2016/03/causal.pdf)
* [The Seven Tools of Causal Inference, with Reflections on Machine Learning](https://cacm.acm.org/magazines/2019/3/234929-the-seven-tools-of-causal-inference-with-reflections-on-machine-learning/fulltext)
* [Graphical & Latent Variable Modeling](https://m-clark.github.io/sem/)
