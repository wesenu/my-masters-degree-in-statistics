# my-masters-degree-in-statistics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources for my custom-designed Master's degree in Statistics with a concentration in Machine Learning at Louisiana State University.     

Yeah, it's a lot! I wanted to learn a variety of interesting topics with connections to Machine Learning, so I ended up taking **a ton of classes**.



# Contents

<!-- START_TOC -->

* [Contents](#contents)
* [Theory](#theory)
    * [Linear Algebra](#linear-algebra)
    * [Numerical Analysis](#numerical-analysis)
    * [Partial Differential Equations](#partial-differential-equations)
    * [Probability and Statistics](#probability-and-statistics)
* [Advanced Theory](#advanced-theory)
    * [Analysis](#analysis)
        * [Real Analysis](#real-analysis)
        * [Measure Theory](#measure-theory)
        * [Stochastic processes](#stochastic-processes)
    * [Convex Optimization](#convex-optimization)
* [Applied](#applied)
    * [Statistical Methods](#statistical-methods)
    * [Statistical Computing](#statistical-computing)
    * [Generalized Linear Models](#generalized-linear-models)
        * [Regression Analysis](#regression-analysis)
        * [Categorical Data Analysis](#categorical-data-analysis)
    * [Time Series Analysis](#time-series-analysis)
        * [Resampling Methods for Time Series](#resampling-methods-for-time-series) 
        * [Time Series Anomaly Detection](#time-series-anomaly-detection)
        * [Time Series Changepoint Models](#time-series-changepoint-models)
    * [Generalized Nonlinear Models](#generlaized-nonlinear-models)
    * [Design of Experiments](#design-of-experiments)
* [Advanced Applied](#advanced-applied)
    * [Computational Linear Algebra](#computational-linear-algebra)
    * [Advanced Statistical Computing](#advanced-statistical-computing)
    * [Bayesian Analysis](#bayesian-analysis)
    * [Multivariate Statistics](#multivariate-statistics)
    * [Statistical Machine Learning](#statistical-machine-learning)
    * [Deep Learning](#deep-learning)
    * [Network Analysis and Causal Inference](#network-analysis-and-causal-inference)
    * [Advanced Statistical Modelling](#advanced-statistical-modelling)
    * [Probabilistic Graphical Models](#probabilistic-graphical-models)
    * [Longitudinal Data Analysis](#longitudinal-data-analysis)
    * [Survival and Reliability Analysis](#survival-and-reliability-analysis)
    * [Databases](#databases)
* [Potential PhD Research Areas](#potential-phd-research-areas)  
    * [Representation Learning](#representation-learning)

* [Personal and Practicuum Consulting Projects](#personal-and-practicuum-consulting-projects)    
* [MOOCs](#moocs) 
* [People and Programs](#people-and-programs)
* [Miscs](#miscs)


<!-- END_TOC -->

***************
********************


# Theory

## Linear Algebra
Probably one of the top 3 most relevant areas of study for statisticians. You could get away with little knowledge in Abstract Algebra, but you really need to master Linear Algebra. Go beyond the usual algebraic matrix calculations - try to get a deep, almost philosphical view on concepts like projectivity, spectral decomposition, sparse matrices, etc. 

* [**Video Lectures: Matrix Methods in Data Analysis, Signal Processing, and Machine Learning**](https://www.youtube.com/playlist?list=PLUl4u3cNGP63oMNUHXqIUcrkS2PivhN3k) - by Gilbert Strang (MIT), [accompanying notes](http://math.mit.edu/~gs/linearalgebra/)
* [Linear Algebra](https://www.cs.cornell.edu/courses/cs485/2006sp/LinAlg_Complete.pdf) - Paul Dawkins (Cornell University)
* [MIT OpenCourseWare Lectures on Linear Algebra as Jupyter Notebooks](https://github.com/juanklopper/MIT_OCW_Linear_Algebra_18_06) - Juan Klopper
* [Introduction to Applied Linear Algebra](https://web.stanford.edu/~boyd/vmls/vmls.pdf) - Stephen Boyd (Stanford University), Lieven Vandenberghe (UCLA)
* [Introduction to vectors and tensors, Vol 1: linear and multilinear algebra](http://oaktrust.library.tamu.edu/handle/1969.1/2502) - Ray M Bowen, C. C. Wang
* [Introduction to vectors and tensors, Vol 2: vector and tensor analysis](http://oaktrust.library.tamu.edu/handle/1969.1/3609) - Ray M Bowen, C. C. Wang    


[**return to contents**](#contents)

********************

## Numerical Analysis

I HATED this subject as an undergrad - I don't recall why though :) Now, I can barely imagine computational statistics without some approximate or numerical solutions. Almost all statistical software provide numerical solutions to all probability distributions, simulation and optimization problems. Again over here, go beyond the usual undergrad numerical topics - at least try numerical implementations/solutions to eigen-problems, smoothing and optimization, splines, random number generation, and Monte Carlo Simulations. This subject also provides good practice in computing and design in general. 


* [A Concise Introduction to Numerical Analysis](http://www.ima.umn.edu/~arnold/597.00-01/nabook.pdf) - Douglas N. Arnold (University of Minnesota)
* [Introduction to Numerical Analysis](https://github.com/mandli/intro-numerical-methods) - Kyle Mandli (Columbia University)
* [Computational Numerical Analysis](http://www.engr.uky.edu/~acfd/egr537-lctrs.pdf) - J. M. McDonough (University of Kentucky)
* [Numerical Analysis for Engineers](https://ece.uwaterloo.ca/~dwharder/NumericalAnalysis/) - Douglas Wilhelm Harder  


[**return to contents**](#contents)

********************

## Partial Differential Equations

Personally, this is the most exciting field in applied math that I have encountered so far. The overarching theme is the relationship between space and time variables to rates of change. I took this class because of its deep connections with uncertainty quantification, optimization, network analysis, image analysis and stochastic DEs (most notably, the Black-Sholes in Options Pricing).

* [Notes on Partial Differential Equations](https://www.math.ucdavis.edu/~hunter/pdes/pde_notes.pdf) - John K. Hunter (University of California at Davis)
* [Computational Numerical PDEs](https://github.com/mandli/numerical-methods-pdes) - Kyle Mandli (Columbia University)   
* [COOL Applications](https://math.berkeley.edu/~sethian/2006/Applications/Menu_Expanded_Applications.html) - by Jamie Sethian (UC - Berkeley)   


[**return to contents**](#contents)

********************

## Probability and Statistics

Well, this section is self explanatory. I will recommend you thoroughly understand the following concepts: Transformations, Independency and Copulas, Convergence, Sufficiency, Parameter Estimation and Inference, and the Exponential Family of Distributions. Dr. Luis Escobar of LSU has amazing lecture notes on these topics.

* [Statistical Inference](https://www.amazon.com/Statistical-Inference-George-Casella/dp/0534243126) - Casella and Berger
* [Stat 414/415](https://newonlinecourses.science.psu.edu/stat414/) - Penn State
* [Introduction to Probability](http://vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf) - Dimitri P. Bertsekas, John N. Tsitsiklis (MIT)
* [A Short Introduction to Probability](http://www.maths.uq.edu.au/~kroese/asitp.pdf) - Dirk P. Kroese (University of Queensland)
* [Probability: Theory and Examples](https://services.math.duke.edu/~rtd/PTE/PTE5_011119.pdf) - Rick Durrett (Duke University)
* [Probability and Statistics Cookbook](https://github.com/mavam/stat-cookbook/releases/download/0.2.3/stat-cookbook.pdf) - Matthias Vallentin (UC Berkeley)  


[**return to contents**](#contents)

********************
********************

# Advanced Theory
Here are the bitter pills that you just have to swallow :)


## Analysis

### Real Analysis

* [MIT OpenCourseWare Lectures on Calculus](https://ocw.mit.edu/resources/res-18-001-calculus-online-textbook-spring-2005/textbook/) - G. Strang
* [An Introduction to Real Analysis](https://www.math.ucdavis.edu/~hunter/intro_analysis_pdf/intro_analysis.pdf) - John K. Hunter (University of California at Davis)
* [Introduction to Real Analysis](http://ramanujan.math.trinity.edu/wtrench/texts/TRENCH_REAL_ANALYSIS.PDF) - William F. Trench (Trinity University, Texas)
* [Basic Analysis: Introduction to Real Analysis](http://www.jirka.org/ra/realanal.pdf) - Jiří Lebl
* [Elementary Real Analysis](http://prac.im.pwr.wroc.pl/~kwasnicki/pl/stuff/tbb-hyper.pdf) - Thomson, Bruckner
* [Lecture Notes in Real Analysis](http://ms.mcmaster.ca/~sawyer/Publications/Real_Analysis.pdf) - Eric T. Sawyer (McMaster University)
* [Real Analysis](http://math.harvard.edu/~ctm/papers/home/text/class/harvard/212a/course/course.pdf) - C. McMullen
* [Real Analysis for Graduate Students](http://bass.math.uconn.edu/3rd.pdf) - Richard F. Bass
* [Modern Real Analysis](http://www.math.purdue.edu/~torres/pubs/Modern-real-analysis.pdf) - William P. Ziemer (Indiana University)
* [Mathematical Analysis Vol I](http://www.trillia.com/zakon-analysisI.html) - Elias Zakon  


[**return to contents**](#contents)

********************

### Measure Theory

* [An Introduction to Measure Theory](https://terrytao.files.wordpress.com/2011/01/measure-book1.pdf) - Terence Tao (UCLA)
* [Lecture Notes in Measure Theory](http://www.math.chalmers.se/~borell/MeasureTheory.pdf) - Christer Borell
* [A Crash Course on the Lebesgue Integral and Measure Theory](http://www.gold-saucer.org/math/lebesgue/lebesgue.pdf) - Steve Cheng
* [Measure Theory](https://www.math.ucdavis.edu/~hunter/measure_theory/measure_notes.pdf) - John K. Hunter (University of California at Davis)
* [Measure and Integration](https://people.math.ethz.ch/~salamon/PREPRINTS/measure.pdf) - Dietmar A. Salamon (ETH Zürich)  

[**return to contents**](#contents)

********************

### Stochastic Processes 

* [Stochastic Processes (Advanced Probability II)](https://www.stat.cmu.edu/~cshalizi/754/) - Cosma Shalizi (Carnegie Mellon University)  
* [Modelling with Stochastic Processes](https://www.stat.ubc.ca/~bouchard/courses/stat547-sp2013-14/index.html) - Alexandre Bouchard-Côté (University of Bristish Columbia)
* [Stochastic Models and Simulation](https://wolfweb.unr.edu/~drschmidt/Stat753/) - Deena Schmidt(University of Nevada, Reno)


********************
********************

## Convex Optimization 

This module is a MUST. Enough said!

* [Convex Optimization](https://see.stanford.edu/Course/EE364A) - Stephen P. Boyd (Stanford University)  
* [Convex Optimization](http://www.stat.cmu.edu/~ryantibs/convexopt/) - Ryan Tibshirani (Carnegie Mellon University)  


[**return to contents**](#contents)

********************
********************

# Applied

## Statistical Methods

This was mostly a slightly refined version of undergrad statistical methods with little bits of design of experiments. This class, I believe, was designed for grad students with little to no background in math/stats. For folks with some stats background, I highly recommend the resources below especially Dr. Cosma Shalizi's book, which is hands down, the best introductory stats book I have ever read.   

* [Advanced Data Analysis from an Elementary Point of View](https://www.stat.cmu.edu/~cshalizi/ADAfaEPoV/ADAfaEPoV.pdf) - Cosma Shalizi (Carnegie Mellon University)
* [Statistical Methods: The Geometric Approach](https://www.springer.com/us/book/9780387975177?gclid=EAIaIQobChMIkP7_gPOv4gIVEpJbCh1A2gFMEAQYAiABEgIoqPD_BwE) - Alan Agresti (University of Florida)
* [Applied Linear Models](https://mysite.science.uottawa.ca/rkulik/mat3378/mat3378-textbook.pdf) - Kutner et al.
* [Design of Experiments](https://newonlinecourses.science.psu.edu/stat503/) - Penn State
* [TA Resource: Applied Statistics with R](https://daviddalpiaz.github.io/appliedstats/) - David Dalpiaz (University of Illinois - Urbana Champaign)
* [GREAT TA Resource: Statistics in Action with R](http://sia.webpopix.org/)

[**return to contents**](#contents)  

********************

## Statistical Computing 

This module is almost as important as Linear Algebra.  

Some of these are more 'pseudo' than actual statistical computing, but very useful content all the same. 

* [Numerical Recipes: The Art of Scientific Computing](https://amzn.to/2WqsWGH) - and [codes site](http://numerical.recipes/routines/instbyfile.html) -William H. Press
* [Statistical Computing Methods](http://www.markirwin.net/stat221/) - Mark Irwin (Harvard University)
* [Statistical Computing](http://www.stat.cmu.edu/~ryantibs/statcomp/) - Ryan Tibshirani (Carnegie Mellon University)  
* [Statistical Computing](https://www.stat.cmu.edu/~cshalizi/statcomp/14/) - Cosma Shalizi (Carnegie Mellon University)     

[**return to contents**](#contents)


********************

## Generalized Linear Models

### Regression Analysis 

This stand-alone class on regression is one of the best classes I took at LSU. The professor,  Dr. Brian Marx, effortlessly walks you through the rationale behind the nitty-gritties of regression and generalized modelling in general. You do not want to miss his classes. Alan Agresti's book below is invaluable!  


* [Regression: Models, Methods and Applications](https://www.springer.com/us/book/9783642343322) - B.D. Marx et al.
* [Introduction to Linear Regression Analysis 5th Edition](https://www.amazon.com/Introduction-Regression-Analysis-Douglas-Montgomery/dp/0470542810) - Montgomery et al.
* [The Truth About Linear Regression](http://www.stat.cmu.edu/~cshalizi/TALR/TALR.pdf) - Cosma Shalizi (Carnegie Mellon University)
* [Foundations of Linear and Generalized Linear Models](https://www.oreilly.com/library/view/foundations-of-linear/9781118730058/) - Alan Agresti (University of Florida)  
* [Extending the Linear Model with R](https://github.com/robjhyndman/ETC3580/blob/master/Faraway%20(2016)%20Extending%20the%20linear%20model%20with%20R.pdf)
* [Example: https://cran.r-project.org/web/packages/BradleyTerryScalable/vignettes/BradleyTerryScalable.html](https://cran.r-project.org/web/packages/BradleyTerryScalable/vignettes/BradleyTerryScalable.html)

[**return to contents**](#contents)

********************


### Categorical Data Analysis

Again Dr. Brian D. Marx does a masterful job at teaching this class. This class introduces the concepts of Generalized Linear Modelling, with the latter half of the class focusing mainly on the analysis of categorical/discrete data. 

* [Categorical Data Analysis](https://www.wiley.com/en-us/An+Introduction+to+Categorical+Data+Analysis%2C+3rd+Edition-p-9781119405269) - Alan Agresti (University of Florida)
* [Resources for Alan Agresti's Books](http://users.stat.ufl.edu/~aa/cda/cda.html)
* [Analysis of Categorical Data with R](http://www.chrisbilder.com/categorical/index.html) - Christopher R. Bilder (University of Nebraska-Lincoln)
* [Analysis of Discrete Data](https://newonlinecourses.science.psu.edu/stat504/node/4/) - Penn State
* [Generalized Linear Models](http://www.markirwin.net/stat149/) - Mark Irwin (Harvard University)
* [Some Projects](https://github.com/topics/categorical-data)

[**return to contents**](#contents)

******************** 

## Generalized Nonlinear Models

Interest in this field after my Fall 2019 summer internship.

Current reading materials is [Generalized Linear and Nonlinear Models for Correlated Data: Theory and Applications Using SAS](https://www.oreilly.com/library/view/generalized-linear-and/9781599946474/).




[**return to contents**](#contents)


********************

## Time Series Analysis  

Best taken after after the modules on Generalized Linear Models. I found Dr. Robert Nau's notes on Time Series Analysis particularly useful. Dr. Shalizi does an equally good job. 

* [Statistical Forecasting: Regression and Time Series](http://people.duke.edu/~rnau/411home.htm) - Robert Nau (Duke University)
* [Data over Space and Time](http://www.stat.cmu.edu/~cshalizi/dst/18/) - Cosma Shalizi (Carnegie Mellon University)
* [Forecasting: Principles and Practice](https://otexts.com/fpp2/) - by [R. J. Hyndman](https://github.com/robjhyndman) and G. Athanasopoulos
* [Forecasting at Scale - Prophet](https://facebook.github.io/prophet/) - Facebook see [good example](https://towardsdatascience.com/implementing-facebook-prophet-efficiently-c241305405a3)
* [Time Series Analysis](https://ocw.mit.edu/courses/economics/14-384-time-series-analysis-fall-2013/) - Standford University
* [Time Series Analysis - GitHub R Codes Repo](https://github.com/nickpoison/tsa4)
* [Little Book of R for Time Series](https://a-little-book-of-r-for-time-series.readthedocs.io/en/latest/)
* [Interesting Examples from Peter Laurinec](https://petolau.github.io/)
* [Example: Time Series with GAM](https://petolau.github.io/Analyzing-double-seasonal-time-series-with-GAM-in-R/)
* [Resource: Time Series Classification News, Algorithms and Sample Codes Archive](http://www.timeseriesclassification.com/index.php) - University of California, Riverside


[**return to contents**](#contents)

### Resampling Methods for Time Series

* [Paper: Resampling strategies for imbalanced time series forecasting](https://link.springer.com/article/10.1007/s41060-017-0044-3) -  Moniz et al. 2017.
* [Paper: The Impact of Bootstrap on Time Series Data](www.math.ucsd.edu/~politis/StatSci03.pdf)
* [Example: Time Series Cross Validation](https://rpubs.com/crossxwill/time-series-cv)
* [Example: Time Series Cross Validation](https://robjhyndman.com/hyndsight/tscv/)


[**return to contents**](#contents)

### Time Series Anomaly Detection

Just follow this amazing group, [**Event and Pattern Detection Laboratory - Carnegie Mellon University**](https://epdlab.heinz.cmu.edu/) and this NYU Professor, [Daniel B. Neill](https://cs.nyu.edu/~neill/selected_pubs_by_topic.html), [(his other link)](https://www.cs.cmu.edu/~neill/papers/)



See below a selection of the most relevant links to me from this [exhaustive list](https://github.com/yzhao062/anomaly-detection-resources)   

* [Outlier Analysis](https://www.springer.com/us/book/9781461463955) - Aggarwal, Charu C.
* [Outlier Ensembles: An Introduction](https://www.springer.com/us/book/9783319547640) - Aggarwal, Charu C., Sathe, Saket
* [Anomaly Detection: A Tutorial](http://webdocs.cs.ualberta.ca/~icdm2011/downloads/ICDM2011_anomaly_detection_tutorial.pdf)
* [Tutorial: Novel Machine Learning Methods for Public Health and Disease Surveillance](https://www.cs.cmu.edu/~neill/papers/biothreats2018.pdf)
* [Tutorial: Efficient Discovery of Heterogeneous Treatment Effects via Anomalous Pattern Detection](https://www.cs.cmu.edu/~neill/papers/TESS2018.pdf)
* [Blog: Anomaly.io](https://anomaly.io/blog/)


[**return to contents**](#contents)


### Some Anomaly Detection Software


| Name          | Language       | Pitch     | License
| ------------- |:-------------: | :-------------: |  :-------------:     
| Twitter's [AnomalyDetection](https://github.com/twitter/AnomalyDetection)| R      |AnomalyDetection is an open-source R package to detect anomalies which is robust, from a statistical standpoint, in the presence of seasonality and an underlying trend.   | GPL
| Linkedin's [luminol](https://github.com/linkedin/luminol)                | Python |Luminol is a light weight python library for time series data analysis. The two major functionalities it supports are anomaly detection and correlation.| Apache-2.0      
| [Donut](https://github.com/korepwx/donut)| Python | Donut is an unsupervised anomaly detection algorithm for seasonal KPIs, based on Variational Autoencoders. | -
| NASA's [Telemanom](https://github.com/khundman/telemanom)| Python | A framework for using LSTMs to detect anomalies in multivariate time series data. Includes spacecraft anomaly data and experiments from the Mars Science Laboratory and SMAP missions.  | [custom](https://github.com/khundman/telemanom/blob/master/LICENSE.txt)
| [banpei](https://github.com/tsurubee/banpei)| Python | Outlier detection (Hotelling's theory) and Change point detection (Singular spectrum transformation) for time-series. | MIT
| [CAD](https://github.com/smirmik/CAD) | Python | Contextual Anomaly Detection for real-time AD on streaming data (winner algorithm of the 2016 NAB competition). | AGPL

[**return to contents**](#contents)

### Time Series Changepoint Models

This content is complementary to [Time Series Anomaly Detection](#time-series-anomaly-detection). 

* [Paper: Bayesian Online Changepoint Detection](https://arxiv.org/abs/0710.3742) - by Ryan Prescott Adams, David J.C. MacKay with some inspired examples like [1](https://github.com/hildensia/bayesian_changepoint_detection), [2](https://github.com/chenhaotian/Changepoints) and [3](http://nowave.it/pages/bayesian-changepoint-detection-with-r-and-stan.html)
* [Paper: A Survey of Methods for Time Series Change Point Detection](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5464762/) - Samaneh Aminikhanghahi and Diane J. Cook
* [Example: Detection of Changes in Signals](http://sia.webpopix.org/changePoints.html)
* [Paper: Detecting Correlation Changes in Multivariate Time Series: A comparison of four non-parametric change point detection methods](https://link.springer.com/article/10.3758/s13428-016-0754-9) - Jedelyn Cabrieto

[**return to contents**](#contents)

********************

## Design of Experiments

Maybe the MVP in the entire masters program. With the current era of 'big data', there is unnecessarily high focus on prediction, but prediction in itself is sometimes useless without control. Randomized experiments is one way to test competing ideas or solutions, and thus control predictions or outcomes. The professor of this course, Dr. David C. Blouin is a seasoned expert in experimental design. I recommend taking this class after taking the linear modelling and or data mining classes because this class (DoE) introduces an almost artistic yet scientific paradigm to problem solving which you would not appreciate if taken prior to taking the latter classes. This class is project-heavy - roughly 2 projects every week - which helps in honing this almost artistic skill.   


Although not necessary, I recommend you take this class simultaneously with an introductory course in **Causal Inference**.

* [Design of Experiments](https://www.springer.com/us/book/9783319522487?gclid=EAIaIQobChMIkPbZq_mv4gIVjbbACh1vLggzEAQYAiABEgJ05_D_BwE) - Dean et al.
* [Desgin of Experiments](http://statweb.stanford.edu/~owen/courses/363/) - Stanford University 
* [Design and Analysis of Experiments - GitHub Repo](https://github.com/fcampelo/Design-and-Analysis-of-Experiments)
* [Elements of Causal Inference: Foundations and Learning Algorithms ](https://mitpress.mit.edu/books/elements-causal-inference) - Peters et al.
* [Tutorial: Online Experiments for Computational Social Science](https://eytan.github.io/www-15-tutorial/) - Eytan Bakshy and Sean J. Taylor 
* [Tutorial: Propensity Score Analysis with R](http://journals.sfu.ca/jmde/index.php/jmde_1/article/download/431/414/) and a [GitHub Repo](https://github.com/jbryer/psa)
* [Lecture Notes: Causal Modeling, Especially Graphical Causal Models](https://www.stat.cmu.edu/~cshalizi/402/lectures/22-causal-models/lecture-22.pdf) - Cosma Shalizi(CMU)
* [Lecture Notes: Estimating Causal Models](https://www.stat.cmu.edu/~cshalizi/402/lectures/23-causal-estimation/lecture-23.pdf) - Cosma Shalizi(CMU)
* [A Crash Course in Causality: Inferring Causal Effects from Observational Data](https://www.coursera.org/learn/crash-course-in-causality)
* [Paper: Social Influence in Social Advertising: Evidence from Field Experiments](https://arxiv.org/pdf/1206.4327.pdf) - Eytan et al. 2012.  


One critique of this class is that there is little emphasis on testable problem formulation - the statistician is relegated to only churning out design solutions (that is, model specification and analysis), and not appropriate problem formulation or experimentation. The book below offers approaches to optimal experimentation for a given problem or purpose. 

* [Book: Optimum Experimental Designs,](https://global.oup.com/academic/product/optimum-experimental-designs-with-sas-9780199296606?cc=us&lang=en&) with [SAS](http://global.oup.com/booksites/content/9780199296606/sas/) - Anthony Atkinson, Alexander Donev, and Randall Tobias  


[**return to contents**](#contents)

*****************
******************


# Advanced

## Computational Linear Algebra

Basically numerical methods to linear algebra

* [Computational Linear Algebra with Python](https://github.com/fastai/numerical-linear-algebra)
* [Computational Linear Algebra Videos](https://www.youtube.com/playlist?list=PLtmWHNX-gukIc92m1K0P6bIOnZb-mg0hY) - Rachel Thomas  

[**return to contents**](#contents)

******************

## Advanced Statistical Computing

Although one of the most important skills a modern statistician needs to acquire, this field is barely teased in graduate statistics programs in the US. You can think of the techniques discussed in this module as machine translations or implementations of statistical algorithms. And provides answers or introduces questions like how computers solve statistical problems. Sampling and/or Resampling techniques, the EM and other deterministic algorithms, and the whole gamut of [Markov Chain] Monte Carlo algorithms including the rather famous Gibbs Sampler, and some popular machine learning optimization algorithms like Stochastic Gradient Descent are discussed. Concepts on convergence and numerical optimization are further explored. Ideas on cloud computing and parallel computing are also introduced.

Best taken in parallel with the Bayesian Analysis and Advanced Statistical Modeling modules, and after the Generalized Linear Models modules. Having a good background in both Linear Algebra and Real Analysis will for sure make life a little easier in this module.  

The **Computing for Data Science** provides a practical introduction to modern techniques for computing with data, teaching advanced use of the R system and exploring connections to other environments such as C, python, Java, and databases. It also provides a hands-on practice on some computing paradigms, including parallel, cluster and map/reduce style computation.


* [**Advanced Statistical Computing with Python**](http://stronginference.com/Bios8366/lectures.html) and accompanying [repo](https://nbviewer.jupyter.org/github/fonnesbeck/Bios8366/tree/master/) - Chris Fonnesbeck (Vanderbilt University)
* [**Computing for Data Science**](http://scpd.stanford.edu/search/publicCourseSearchDetails.do?method=load&courseId=5370712) - John Chambers and Balasubramanian Narasimhan (Stanford University)  
* [**Computational Statistics with Python**](https://people.duke.edu/~ccc14/sta-663/) - Duke University
* [Book: Introducing Monte Carlo Methods with R](https://www.springer.com/us/book/9781441915757) - Christian Robert and George Casella
* [Open Source Book: Advanced Statistical Computing with R](https://bookdown.org/rdpeng/advstatcomp/) - Roger D. Peng (John Hopkins University)
* [Book: An Introduction to Scientific Programming and Simulation Using R.](https://www.crcpress.com/Introduction-to-Scientific-Programming-and-Simulation-Using-R/Jones-Maillardet-Robinson/p/book/9781466569997) - Jones, Owens; Maillardet, Robert & Robinson, Andrew. (2011).  



[**return to contents**](#contents)

******************

## Bayesian Analysis

I struggled in this class partly because I had a terrible load of 18 credits that semester - which is A LOT for graduate shool. I spent the subsequent semester vacation reviewing the material and I found it surprisingly coherent and accessible. I found reading materials from other schools and practicing the coding very useful.   

I have come to like it so much that I am even considering a lifetime of research in Bayesian frameworks.

I would strongly recommend the following materials first before any advanced material:  

* [Statistical Rethinking](https://github.com/rmcelreath/statrethinking_winter2019) - Richard McElreath  
* [Bayesian Data Analysis](https://github.com/avehtari/BDA_course_Aalto) - Aki Vehtari 


As always, it is good to look up the similar content from other schools or programs:


* [Bayesian Methods and Modern Statistics - Course GitHUb Repo](https://github.com/resteorts/modern-bayes) - Rebecca Steorts (Duke University) 
* [Bayesian Methods and Modern Statistics - Course Website](http://www2.stat.duke.edu/~rcs46/bayes18.html) - Rebecca Steorts (Duke University)
* [Applied Bayesian Analysis](https://www4.stat.ncsu.edu/~reich/ABA/index.html) - Brian Reich (North Carolina State University)
* [Bayesian Inference](https://www4.stat.ncsu.edu/~reich/ST740/) - Brian Reich (North Carolina State University)
* [Think Bayes](http://greenteapress.com/wp/think-bayes/) - Allen B. Downey
* [Book: A First Course in Bayesian Statistical Methods](https://www.springer.com/us/book/9780387922997) - Peter D. Hoff
* [Book: Bayesian Computation with R by Jim Albert](https://www.springer.com/us/book/9780387922973) and [Book's site with R Scripts, Notebooks and Blogposts](http://www-math.bgsu.edu/~albert/bcwr/)
* [Book: Introducing Monte Carlo Methods with R](https://www.springer.com/us/book/9781441915757) - Christian Robert and George Casella
* [Probabilistic Programming and Bayesian Methods for Hackers - GitHub Repo](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - Cameron Davidson-Pilon
* [Bayesian Modelling with Python](https://github.com/markdregan/Bayesian-Modelling-in-Python)
* [Probabilistic Programming and Bayesian Methods for Hackers - Website](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) - Cameron Davidson-Pilon
* [Bayesian Modeling and Inference](https://people.eecs.berkeley.edu/~jordan/courses/260-spring10/) - Michael Jordan(UC - Berkeley)
* [Learning Bayes](http://florianhartig.github.io/LearningBayes/)  

[**return to contents**](#contents)

*************************

## Multivariate Statistics

I took this class after the GLM modules - it kind of made this class at LSU is somewhat redundant. I suggest you read on the freely available NC State class on Nonlinear Models for Univariate and Multivariate Response as a supplement.   

This course is extremely vital if you are interested in any high dimensional statistics or manifold learning in general. So I suggest you look elsewhere for relevant materials.


* [Applied Multivariate Methods for Data Analysts](https://www.amazon.com/Applied-Multivariate-Methods-Data-Analysts/dp/0534237967) - Dallas E. Johnson
* [A First Course in Structural Equation Modeling, 2nd ed.](https://www.amazon.com/First-Course-Structural-Equation-Modeling/dp/0805855882) - Tenko et al.
* [Applied Multivariate Analysis](https://onlinecourses.science.psu.edu/stat505/) - Penn State
* [Nonlinear Models for Univariate and Multivariate Response](https://www.stat.ncsu.edu/people/davidian/courses/st762_fall2009//) - Marie Davidian (NC State University)

[**return to contents**](#contents)

************************* 


## Statistical Learning 

With the recent 'Data Science' craze there is a litany of dumbed-down materials on SL. Although good for beginners, these are woefully lacking for statisticians hoping to engineer new methodologies, improve or critique current techniques.  

Dive into these as much as you can - they are the best materials on Introduction to Statistical Machine Learning out there. Take key note of concepts regarding **RE-presentation** of data, and projectivity.

* [Advanced Topics in Statistical Modelling](http://statweb.lsu.edu/faculty/li/teach/exst7152/) - Bin Li (Louisiana State University)
* [Statistical Machine Learning](http://www.stat.cmu.edu/~ryantibs/statml/) R. Tibshirani and L. Wasserman (Carnegie Mellon University)
* [Data Mining](https://www.stat.cmu.edu/~cshalizi/350/) Cosma Shalizi (Carnegie Mellon University)
* [Book: An Introduction to Statistical Learning with Applications in R](http://www-bcf.usc.edu/~gareth/ISL/) - Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani
* [Book: The Elements of Statistical Learning: Data Mining, Inference, and Prediction](https://web.stanford.edu/~hastie/ElemStatLearn/) - Trevor Hastie, Robert Tibshirani and Jerome Friedman
* [Book: Computer Age Statistical Inference](https://web.stanford.edu/~hastie/CASI/) - Bradley Effron and Trevor Hastie
* [MOOC: Outlier Detection Algorithms in Data Mining and Data Science](https://www.udemy.com/outlier-detection-techniques/)
* [Blog Post: Winning Solutions - Kaggle Competitions](https://www.kaggle.com/sudalairajkumar/winning-solutions-of-kaggle-competitions)  

[**return to contents**](#contents)

********************

## Deep Learning   

**Stanford Univeristy** has made this topic and all its allied topics amazingly accessible, and freely available online. Just burry yourself in these 4 classes on Deep Learning:  

* [CS230 Deep Learning](https://cs230.stanford.edu/)  
* [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)  
* [CS224n: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/)   
* [STATS 385: Analyses of Deep Learning](https://stats385.github.io/)


I found these other materials also useful:  


* [Machine Learning - Stanford](https://class.coursera.org/ml-005) by Andrew Ng in Coursera (2010-2014)
* [Deep Learning with Python](faculty.neu.edu.cn/yury/AAI/Textbook/Deep%20Learning%20with%20Python.pdf) - Francois Chollet
* [Deep Learning](http://www.deeplearningbook.org/) by Yoshua Bengio, Ian Goodfellow and Aaron Courville  (05/07/2015)
* [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) by  Michael Nielsen (Dec 2014)
* [Artificial Intelligence: A Modern Approach](http://aima.cs.berkeley.edu/)
* [Artificial intelligence and machine learning: Topic wise explanation](https://leonardoaraujosantos.gitbooks.io/artificial-inteligence/)
* [MOOC: Advanced Deep Learning with Keras](https://www.datacamp.com/courses/advanced-deep-learning-with-keras-in-python) by [Zach Mayer](https://github.com/zachmayer)   

[**return to contents**](#contents)

*******************

## Network Analysis and Causal Inference

Discovering this area of statistics has been more than fulfilling - it bridges several disciplines like Philosophy (although more subtly), Behavorial Psychology and Economics, Geometric Topology and Probabilistic Modelling. I have dedicated most of my weekends perusing as much material on these topics as I can.   

My current reading materials or courses are based on the following:  

* [Statistical Network Analysis](https://www.stat.cmu.edu/~cshalizi/networks/16-1/) - Cosma Shalizi (Carnegie Mellon University)
* [Advanced Statistical Network Models](https://www.stat.cmu.edu/~cshalizi/networks/16-2/) - Cosma Shalizi (Carnegie Mellon University)
* [Social and Information Network Analysis](http://snap.stanford.edu/class/cs224w-2016/handouts.html) - Jure Leskovec (Stanford University)  
* [Machine Learning with Graphs](http://web.stanford.edu/class/cs224w/) - Jure Leskovec (Stanford University)  
* [Networks, Crowds, and Markets: Reasoning About a Highly Connected World](http://www.cs.cornell.edu/home/kleinber/networks-book/) -  David Easley and Jon Kleinberg
* [Statistical Analysis of Network Data with R](https://link.springer.com/book/10.1007%2F978-1-4939-0983-4) - Eric D. KolaczykGábor Csárdi
* [Bayesian Networks: With Examples in R](https://www.crcpress.com/Bayesian-Networks-With-Examples-in-R/Scutari-Denis/p/book/9781482225587) - Marco Scutari, Jean-Baptiste Denis
* [Bayesian Network in R with Applications in Systems Biology](https://link.springer.com/book/10.1007%2F978-1-4614-6446-4) - Radhakrishnan NagarajanMarco ScutariSophie Lèbre.  
* [Data Science and Complex Networks: Real Case Studies with Python](https://global.oup.com/academic/product/data-science-and-complex-networks-9780199639601?cc=us&lang=en&) - Guido Caldarelli and Alessandro Chessa
* [A Crash Course in Causality: Inferring Causal Effects from Observational Data](https://www.coursera.org/learn/crash-course-in-causality)  
* [Lecture Notes: Causal Modeling, Especially Graphical Causal Models](https://www.stat.cmu.edu/~cshalizi/402/lectures/22-causal-models/lecture-22.pdf) - Cosma Shalizi(CMU)
* [Lecture Notes: Estimating Causal Models](https://www.stat.cmu.edu/~cshalizi/402/lectures/23-causal-estimation/lecture-23.pdf) - Cosma Shalizi(CMU)
* [A Crash Course in Causality: Inferring Causal Effects from Observational Data](https://www.coursera.org/learn/crash-course-in-causality)
* [Example: Exponential Random Graph Modelling](http://rstudio-pubs-static.s3.amazonaws.com/329810_72b09e66276044949bc3bdc2cfcd6161.html)

[**return to contents**](#contents)

*******************


## Advanced Statistical Modelling  

This module is a revisit of Generalized Linear Modelling and Statistical Machine Learning that emphasize model building skill and intuition with relatively advanced statistical rigor and computation.  Empirical model selection techniques (e.g. basis degree, effective degrees of freedom) and regularization, and extensions to linear regression via basis functions and kernels are further explored. The relationship between randomness and determinism is also further probed. 


* [Advanced Topics in Statistical Modelling](http://statweb.lsu.edu/faculty/li/teach/exst7152/) - Bin Li (Louisiana State University)
* [Chaos, Complexity, and Inference](https://www.stat.cmu.edu/~cshalizi/462/) - Cosma Shalizi (Carnegie Mellon University)
* [Statistical Methods for Analysis With Missing Data](https://www4.stat.ncsu.edu/~davidian/st790/) - Marie Davidian(NC State University)
* [Example: Preprocessing Data with Caret](http://rismyhammer.com/ml/Pre-Processing.html)
* [Paper: Flexible Smoothing with B-Splines and Penalties](https://projecteuclid.org/euclid.ss/1038425655) - Paul H. C. Eilers and Brian D. Marx
* [Paper: Importance Sampled Learning Ensembles](http://statweb.stanford.edu/~jhf/ftp/isle.pdf) - Friedman and Popescu
* [Paper: Gradient Directed Regularization](http://statweb.stanford.edu/~jhf/ftp/pathlite.pdf) - Friedman and Popescu
* [Paper: Predictive Learning vis Rule Ensembles](http://statweb.stanford.edu/~jhf/ftp/RuleFit.pdf) - Friedman and Popescu
* [Paper: Kernels and Ensembles: Perspectives on Statistical Learning](http://www.math.uwaterloo.ca/~m3zhu/papers/TAS2008.pdf) - Mu Zhu
* [Book: Generalized Additive Models: An Introduction with R, Second Edition](https://www.crcpress.com/Generalized-Additive-Models-An-Introduction-with-R-Second-Edition/Wood/p/book/9781498728331) - Simon N. Wood
* [Simon Wood's Website](https://people.maths.bris.ac.uk/~sw15190/)
* [MOOC: Nonlinear Models with GAM](https://www.datacamp.com/courses/nonlinear-modeling-in-r-with-gams)
* [Example: An introduction to Generalized Additive Models with R](https://github.com/gavinsimpson/gams-yorku-canada-150)
* [Example: Generalised Additive Mixed Models](https://github.com/stefanocoretta/gamm-workshop/blob/master/gamm-presentation.pdf)
* [Paper: Convex Regression With Interpretable Sharp Partitions](http://jmlr.org/papers/v17/15-344.html) - Ashley Petersen, Noah Simon, Daniela Witten  
* [Tutorial: Information Filtering for arXiv.org: Bandits, Exploration vs. Exploitation, and the Cold Start Problem](https://people.orie.cornell.edu/pfrazier/Presentations/2014.01.Lancaster.Arxiv.pdf) - Peter Frazier (Cornell University)


[**return to contents**](#contents)

*************************

## Probabilistic Graphical Models  

* [Probabilistic Graphical Models](https://cs.stanford.edu/~ermon/winter17-cs228/index.html) - Stefano Ermon (Stanford University)
* [Probabilistic Graphical ModelsProbabilistic Graphical Models](http://www.cs.cmu.edu/~epxing/Class/10708-14/lecture.html) - Eric Xing (Carnegie Mellon University)

[**return to contents**](#contents)

**********************

## Longitudinal Data Analysis

I took this class simultaneously with Dr. Kevin S. McCarter's Multivariate Analysis.  

* [Longitudinal Data Analysis](https://www4.stat.ncsu.edu/~davidian/st732/) - Marie Davidian(NC State University)
* [Applied Multivariate and Longitudinal Data Analysis](https://www.stat.ncsu.edu/people/staicu/courses/st495-590/index.html)
* [Tutorial: Propensity Score Matching](https://sejdemyr.github.io/r-tutorials/statistics/tutorial8.html)

[**return to contents**](#contents)

*************************

## Survival and Reliability Analysis

Spontaneous and somewhat hobby-like reading on:

* [Introduction to Survival Analysis](https://lifelines.readthedocs.io/en/latest/Survival%20Analysis%20intro.html)   


I have also been trying to learn how to model survival data with Deep Learning algorithms by reading some of the papers from the link below. 

* [Survial Analysis using Deep Learning](https://github.com/robi56/Survival-Analysis-using-Deep-Learning/blob/master/README.md)


[**return to contents**](#contents)


*************************

## Databases 
* [Database Systems - Carnegie Mellon University](https://15445.courses.cs.cmu.edu/fall2018/)
* [Introduction to Databases - Stanford Lagunita](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/)    

[**return to contents**](#contents)

*************************
*************************


# Potential PhD Research Areas

soon...

*************************
# Personal and Practicuum Consulting Projects  

soon...

*************************

# MOOCs

List incomplete...

* [Mining Massive Datasets](https://lagunita.stanford.edu/courses/course-v1:ComputerScience+MMDS+SelfPaced/about) - Stanford University Online (Lagunita)
* [Data Intensive Scientific Computing](https://edge.edx.org/courses/course-v1:NotreDame+00000+00/about) - edX (University of Notre Dame)
* [Convolutional Neural Networks for Text](https://www.youtube.com/watch?v=vnzKAhs7nds&index=5&list=PL8PYTP1V4I8ABXzdqtOpB_eqBlVAz_xPT) - Graham Neubig (Carnegie Mellon University)
* [Big Data Analytics Using Spark](https://www.edx.org/course/big-data-analytics-using-spark-uc-san-diegox-dse230x) - edX (UC San Diego)
* [The Ultimate Hands-On Hadoop - Tame your Big Data](https://bit.ly/2XlC4tB) - Udemy
* [High-performance Computing for Reproducible Genomics](https://www.edx.org/course/high-performance-computing-reproducible-harvardx-ph525-6x-1) - edX (Harvard University)
* [Data Visualization and D3.js](https://www.udacity.com/course/data-visualization-and-d3js--ud507) - Udacity, and a [ton of Tutorials](https://github.com/d3/d3/wiki/Tutorials)
* [CS50's Web Programming with Python and JavaScript](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript) - edX (Harvard University)



[**return to contents**](#contents)

*************************

# People and Programs

soon...

*************************

# Miscs

soon...


*************************
*************************