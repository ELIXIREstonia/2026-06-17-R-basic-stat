# 2026-06-17-R-basic-stat

ELIXIR-EE training course on introduction to statistics in R. This course gives PhD students in chemistry, gene technology and food technology hands-on experience with applying basic statistical analysis techniques to research data. The course draws on materials from https://sib-swiss.github.io/Introduction-to-statistics-with-R/

This course is a mixture of lectures and practicals. The main files for practising are:

- **Day 1** — [2026-06-17-R-basic-stat.Rmd](2026-06-17-R-basic-stat.Rmd): EDA, two-group comparisons (paired & two-sample t-tests, Mann-Whitney, Wilcoxon signed-rank). Power analysis appendix for self-study.
- **Day 2** — [2026-06-18-R-basic-stat.Rmd](2026-06-18-R-basic-stat.Rmd): multiple testing correction, ANOVA + Tukey, Kruskal-Wallis + Dunn, multi-factorial ANOVA, correlation, linear regression, categorical data (Chi-square, Fisher's exact, odds ratio). Appendices (self-study): polynomial regression, ANOVA-as-LM, linear mixed models.

R Markdown allows code (examples) and explanation / documentation to be in the same document in a nicely formatted, well structured manner.

Data files needed in the code are located in the `data` folder. Domain-relevant datasets include:

- `catalyst_yield.csv` — reaction yields for 4 catalysts (chemistry; ANOVA);
- `fermentation.csv` — lactic acid concentration over time for two starter cultures (food technology; regression/correlation);
- `qpcr_expression.csv` — paired ΔCt values, control vs treated (gene technology; paired t-test);
- `PlantGrowth.csv` — additional example data.

The lecture slides are found in the `slides` folder

Learning outcomes:

1.  **Have experience applying basic statistics techniques in R**:

    -   Learners will be able use R to run appropriate statistical tests and visualize these results.

2.  **Summarize data with numerical and graphical summaries**:

    -   Participants will gain proficiency in ggplot library and learn to summarize data.

3.  **Understanding basic concepts in statistics: one/two/multiple-sample tests, hypothesis testing, multiple testing correction etc.**:

    -   Trainees will be equipped with the knowledge about which statistical test to apply and when, how to do hypothesis testing in biological context and when to apply multiple testing.

4.  **Learn about the relations in the data using correlation, regression**:

    -   Learners will find out about relations between features in data.
      
5.  **Understand how to deal with categorical data in statistics**:

    -   Learners will gain understanding about how to find statistical significant associations in categorical data. 

### Next step

If you are more interested in creating compelling visualisations using R and ggplot2, check out the previous training: [https://github.com/ELIXIREstonia/2024-06-18-R-visualisation](https://github.com/ELIXIREstonia/2024-06-18-R-visualisation)
