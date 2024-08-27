Hi! I have been working on machine learning and statistical software
(especially using R/Python/C/C++/JavaScript) since my undergrad in
Berkeley Stats (BA 2006), and my PhD in Paris (2012). Since 2024 I
work as a Tenured Associate Professor in Université de Sherbrooke,
Département d'Informatique, where I direct the [LASSO research
lab](https://lassolab.org/) (Learning Algorithms, Statistical
Software, Optimization). 
See [my web page for complete
CV](https://tdhock.github.io/).

I have published 40+ peer-reviewed research papers on machine learning and statistical software. 
My research emphasizes fast, accurate, and interpretable algorithms for learning from large data, using continuous optimization (clustering, regression, ranking, classification) and discrete optimization (changepoint detection, dynamic programming). The main application domains for these algorithms are genomics, neuroscience, medicine, microbiome, cybersecurity, robotics, satellite/sonar imagery, climate/carbon modeling. [See my Publications page for more info](https://tdhock.github.io/publications/).

I have mentored 30+ students in research projects, as well as another 30+ open-source software contributors with R Project in Google Summer of Code.
[See my Teaching page for a list of students mentored](https://tdhock.github.io/teaching/).

I think reproducible research is important, so in addition to every research paper, I also provide

* Source code for doing the analyses and creating the figures,
  typically in a GitHub repo. [See "Reproducible" links on my
  Publications page](https://tdhock.github.io/publications/).
* A reference implementation of the algorithm(s) described in the
  paper, typically as an R package. [See my Software
  page](https://tdhock.github.io/software/).
  
Below is a summary of selected software that I have authored or co-authored.

### Supervised machine learning

* [penaltyLearning](https://github.com/tdhock/penaltyLearning): supervised learning algorithms for predicting penalty values in labeled optimal change-point problems.
* [aum](https://github.com/tdhock/aum): Area Under Min(FP,FN), a new loss function for imbalanced classification and supervised changepoint detection.
* [mlr3resampling](https://github.com/tdhock/mlr3resampling): new cross-validation algorithms for mlr3 framework in R.
* [mmit](https://github.com/aldro61/mmit): Max Margin Interval Trees, decision tree learning for regression with interval-censored outputs.
* [rankSVMcompare](https://github.com/tdhock/rankSVMcompare): support vector machine for learning ranking and comparison functions from labeled pairs of observations.
* [WeightedROC](https://github.com/tdhock/WeightedROC): efficient computation of ROC curves and AUC for binary classification data sets with weights.

### Unsupervised learning

* [clusterpath](http://clusterpath.r-forge.r-project.org/): convex optimization algorithms for clustering, using fusion penalties.

### Change-point detection

* [binsegRcpp](https://github.com/tdhock/binsegRcpp): efficient implementation of the classic binary segmentation heuristic algorithm for change-point detection in sequential data.
* [LOPART](https://github.com/tdhock/LOPART): Labeled Optimal Partitioning, quadratic time dynamic programming algorithm for optimal change-point detection in labeled data sequences.
* [FLOPART](https://github.com/tdhock/FLOPART): Functional Labeled Optimal Partitioning, log-linear time dynamic programming algorithm for optimal change-point detection in labeled count data sequences.
* [gfpop](https://github.com/vrunge/gfpop): Generalized Functional Pruning Optimal Partitioning, log-linear time dynamic programming algorithm for optimal change-point detection using a graph to define constraints on adjacent segment parameters.
* [PeakSegDisk](https://github.com/tdhock/PeakSegDisk): disk-based dynamic programming algorithm, which uses log-linear time and log memory, for up-down constrained change-point detection in count data sequences.
* [PeakSegJoint](https://github.com/tdhock/PeakSegJoint): heuristic algorithm for detecting a single common peak in several aligned count data sequences.

### Software testing and R package development

* [atime](https://github.com/tdhock/atime): asymptotic time complexity estimation, comparative benchmarking, performance testing.
* [RcppDeepState](https://github.com/FabrizioSandri/RcppDeepState): fuzz testing compiled code in Rcpp packages.
* [inlinedocs](https://github.com/tdhock/inlinedocs): documentation generation for R packages.

### Data visualization

* [animint2](https://github.com/tdhock/animint2): animated, interactive grammar of graphics.
* [directlabels](https://github.com/tdhock/directlabels): automatic direct label placement for multi-color plots.

### Data reading, manipulation, analysis

* [nc](https://github.com/tdhock/nc): named capture regular expressions in R.
* [data.table](https://github.com/rdatatable/data.table): efficient data reading, manipulation and analysis in R.
