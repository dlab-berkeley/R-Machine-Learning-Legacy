# D-Lab R Machine Learning with tidymodels 

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FR-Machine-Learning&urlpath=rstudio%2F&branch=main)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/R-Machine-Learning/HEAD?urlpath=rstudio)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)


This repository contains the materials for D-Lab's R Machine Learning with
tidymodels. Prior experience with the concepts in [R
Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals) and [Data
Wrangling and Manipulation in
R](https://github.com/dlab-berkeley/R-Data-Wrangling) is assumed. 

## Workshop Goals 

In this workshop, we provide an introduction to machine learning algorithms by
making use of the `tidymodels` package. First, we discuss what machine learning
is, what problems it works well for, and what problems it might work less well
for. Then, we'll explore the `tidymodels` framework to learn how to fit machine
learning models in R. Finally, we will apply the `tidymodels` framework to
explore multiple machine learning algorithms in R. 

By the end of the workshop, learners should feel prepared to explore machine learning approaches for their data problems. 

Familiarity with R programming and data wrangling is assumed. If you are not familiar with the materials in [Data Wrangling and Manipulation in R](https://github.com/dlab-berkeley/R-Data-Wrangling), we recommend attending that workshop first. In addition, this workshop focuses on how to implement machine learning approaches. Learners will likely benefit from previous exposure to statistics. 

## Installation Instructions

We will use RStudio to go through the workshop materials, which requires the installation of both the R language and the RStudio software. Complete the following steps:

1. [Download R](https://cloud.r-project.org/): Follow the links according to the operating system that you are running. Download the package, and install R onto your computer. You should install the most recent version (at least version 4.0).

2. [Download RStudio](https://rstudio.com/products/rstudio/download/#download): Install RStudio Desktop. This should be free. Do this after you have already installed R. The D-Lab strongly recommends an RStudio edition of 2022.02.0+443 "Prairie Trillium" or higher. 
 
3. [Download these workshop materials](https://github.com/dlab-berkeley/R-Machine-Learning): 

* Click the green "Code" button in the top right of the repository information.
* Click "Download Zip".
* Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

4. Optional: if you're familiar with `git`, you can instead clone this repository by opening a terminal and entering `git clone git@github.com:dlab-berkeley/R-Machine-Learning.git`.

5. Be sure to run the `install.R` script in the repository so that all necessary
packages are installed.

## Is R Not Working on Your Laptop?

This workshop makes use of many packages within the R ecosystem. For that
reason, we recommend using R on your local machine. 

If you do not have R installed and the materials loaded on your workshop by the time it starts, we *strongly* recommend using the UC Berkeley DataHub to run the materials for these lessons. You can access the DataHub by clicking the following button:

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FR-Machine-Learning&urlpath=rstudio%2F&branch=main)

Some users may have to click the link twice if the materials do not load initially.

The DataHub downloads this repository, along with any necessary packages, and
allows you to run the materials in an RStudio instance on UC Berkeley's servers.
No installation is needed from your end - you only need an internet browser and
a CalNet ID to log in. By using the DataHub, you can save your work and come
back to it at any time. When you want to return to your saved work, go straight
to [DataHub](https://dlab.datahub.berkeley.edu), sign in, and click on the
`R-Machine-Learning` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in the
cloud, by clicking this button:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/R-Machine-Learning/HEAD?urlpath=rstudio)

If you are loading Binder with this repository for the first time, it may take a
few minutes to set up. Binder operates similarly to the D-Lab DataHub, but on a
different set of servers. By using Binder, however, you cannot save your work.

## Run the Code

Now that you have all the required software and materials, you need to run the
code:

1. Launch the RStudio software.

2. Use the file navigator to find the `R-Machine-Learning` folder you downloaded
   from Github.

3. Open up the file corresponding to the part of the workshop you're attending.

4. If necessary, run `install.R` to make sure the requisite packages are
installed. This should not be necessary on Binder.

4. Place your cursor on a given line and press "Command + Enter" (Mac) or
   "Control + Enter" (PC) to run an individual line of code. 

5. The `solutions` folder contains the solutions to the challenge problems.

## Additional Resources 

This workshop draws heavily on the following resources: 

* [*Tidy Modeling with R* by Max Kuhn and Julia Silge](https://www.tmwr.org/).

* [*An Introduction to Statistical Learning* by James, Witten, Hastie, and Tibshirani](https://www.statlearning.com/)

* ["Machine Learning Methods Economists Should Know About" by Athey and Imbens](https://arxiv.org/abs/1903.10075)

* [*Feature Engineering and Selection: A Practical Approach for Predictive Models* by Kuhn and Johnson (2019)](http://www.feat.engineering/data-splitting.html)

* [*The Elements of Statistical Learning* by Hastie, Friedman, and Tibshirani](https://link.springer.com/book/10.1007/978-0-387-21606-5)

* [*Deep Learning* by Goodfellow, Bengio, and Courville](https://www.deeplearningbook.org/)

## Other D-Lab R Workshops

### Basic Competency 

- [R Data Wrangling](https://github.com/dlab-berkeley/R-Data-Wrangling)
- [R Graphics with ggplot2](https://github.com/dlab-berkeley/R-graphics)
- [R Functional Programming](https://github.com/dlab-berkeley/R-functional-programming)
- [Project Management in R](https://github.com/dlab-berkeley/efficient-reproducible-project-management-in-R)
- [Geospatial Fundamentals in R with sf](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-R-with-sf)
- [Census Data in R](https://github.com/dlab-berkeley/Census-Data-in-R)

### Intermediate/Advanced Competency

- [Unsupervised Learning in R](https://github.com/dlab-berkeley/Unsupervised-Learning-in-R)
- [Introduction to Deep Learning in R](https://github.com/dlab-berkeley/Deep-Learning-in-R)
- [Fairness and Bias in Machine Learning](https://github.com/dlab-berkeley/fairML)
- [R Package Development](https://github.com/dlab-berkeley/R-package-development)

## Contributors 

* [Alex Stephenson](https://github.com/asteves/)
* Pratik Sachdeva
* Hero Ashman

Previous iterations of D-Lab's Machine Learning with R were created by: 

- [Chris Kennedy](https://ck37.com/)
- [Evan Muzzall](https://github.com/EastBayEv)
- [Jae Yeon Kim](https://jaeyk.github.io/)
- [Christopher Hench](https://github.com/henchc)
