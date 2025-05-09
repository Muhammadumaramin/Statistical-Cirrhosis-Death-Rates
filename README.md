# Statistical Exploration and Inference of Cirrhosis Death Rates: A Comprehensive Study on Skewness Correction, Outlier Analysis, and Enhancement ofNormality and Statistical Validity.
This project investigates cirrhosis-related mortality across U.S. states using statistical inference techniques. The analysis includes data exploration, assessment of normality, outlier treatment, data transformation, and hypothesis testing to determine whether the average death rate is significantly different from a national reference threshold.
# Objectives:
> Explore and summarize cirrhosis death rate data.
> Assess the distribution for skewness and outliers.
> Apply transformations to improve normality.
> Construct a 95% confidence interval for the mean.
> Perform hypothesis testing against a benchmark (48.33 deaths per 100,000).
> Compare multiple transformation techniques (log, square root).
> Evaluate the impact of retaining vs. removing outliers.
# Project Structure:
├── data/
│   └── cirrhosis_death_rate.csv
├── scripts/
│   └── analysis.R
├── results/
│   ├── graphs/
│   ├── summary_tables/
│   └── hypothesis_tests/
├── README.md
└── report/
    └── final_report.pdf
# Results:
The comprehensive statistical analysis of cirrhosis death rate data across various states led to several important findings. Initial exploration revealed that the original data was heavily right-skewed, with a fewstates exhibiting exceptionally high death rates. Visual inspections through boxplots and histograms, coupled with formal normality tests, confirmed that the original dataset did not satisfy the assumptions necessary for classical inferential procedures. The presence of extreme values raised concerns about the influence of outliers, but rather than removing these observations, a decision was made to retain them, acknowledging that they represented real public health phenomena rather than measurement errors.

To address the skewness and stabilize variance, a natural logarithmic transformation was applied. Post-transformation evaluations, including histograms, Q-Q plots, and the Shapiro-Wilk normality test, indicated a substantial improvement in the distribution’s symmetry, validating the effectiveness of the transformation. This adjustment allowed for the appropriate application of parametric inferential techniques.

The construction of a 95% confidence interval for the mean death rate revealed that the true mean likely falls between approximately 56.53 and 70.46 deaths, suggesting that cirrhosis mortality is a significant public health concern across the states. Furthermore, hypothesis testing was conducted to investigate whether the true mean death rate was lower than the benchmark of 48.33 deaths, as suggested by health authorities. The results of the one-sample, left-tailed t-test provided strong evidence against the hypothesis that the mean was below 48.33. Instead, the findings indicated that the average cirrhosis death rate is significantly higher than the health department’s threshold.

Two key conclusions can be drawn from this study. First, the cirrhosis death rate in the sampled states is higher than previously assumed, signaling a potential need for enhanced public health interventions. Second, the thoughtful application of data transformation techniques, rather than exclusion of outliers, proved essential for conducting valid statistical inference, demonstrating that real-world health data can be rigorously analyzed while preserving its complexity. These results highlight the importance of robust preprocessing and careful methodological choices in public health data analysis.
 
# First Conclusion: True mean death rate is higher than health department’s threshold.
# Second Conclusion: Transformation and retaining outliers led to valid, meaningful inference.

> The original data was right-skewed with several high outliers.
> Log transformation corrected skewness and enabled reliable inference.
> The 95% confidence interval for the mean death rate was (56.53, 70.46).
> Hypothesis testing indicated strong evidence that the mean is greater than 48.33.
> Retaining outliers preserved real-world variation without compromising statistical validity.
