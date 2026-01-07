This report analyzes the average maximum back squat, in Kilograms, for Male Power Lifters around the
world. In particular, we will be focusing on official competition results of lifters from the United States,
China, Russia, Poland, and United Kingdom. A Bayesian Hierarchical Linear Model, assuming random
intercepts, is performed to investigate if the population average maximum back squat for male
professional power lifters is the same for all 5 nations. After observing data, pairwise comparisons and
other Bayesian techniques suggest the contrary. Particularly, it is estimated that China and Poland are
the strongest of the nations, while the UK and USA are the weakest. While Bayesian Statistics will not
always provide direct results of a distinct difference between National Means, we will use a combination
of Frequentest and Bayesian analyses to do this.

- R was the primary language used to contruct this report (tidybayes, brms, lme4, tidyverse, bayesplot))

Below is a breakdown of the content you will see in this report:
1. Inlcusion Criteria and Data Cleaning
2. Verification of Validity Conditions under a Bayesian Heirarchal Linear Model
3. Prior Assumptions, Distributions, and Interpretations
4. Prior Distributions and Prior Predictive Tuning
5. Posterior Distributions and Predictions and Credibility Checks
6. Comparing Nations with Individual and Pairwise Posterior Distributions
7. Frequentist Procedure and Comparison to Bayesian Method
