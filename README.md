```
# R_markdown_result_-有下标

A significant main effect of valence (positive, negative) on the judgments of truth ($t_{`r sum_Ttest_GT$df[3] `, `r sum_Ttest_GT$df[2]`}$ = `r (sum_Ttest_GT$coefficients[2,3])` , _p_ = `r f_num(sum_Ttest_GT$coefficients[2,4], digits= 3)`) was found, with positively valenced claims (_M_ = `r Descriptives_GT_TTEST[["Positive"]][["mean"]][6]`, _SD_ = `r Descriptives_GT_TTEST[["Positive"]][["sd"]][6]`) receiving higher scores on truth than negatively valenced ones (_M_ = `r Descriptives_GT_TTEST[["Negative"]][["mean"]][6]`, _SD_ = `r Descriptives_GT_TTEST[["Negative"]][["sd"]][6]`). 

Additionally no significant interaction was found between valence and group membership (ingroup, outgroup) on the judgments of truth ($t_{`r sum_Interaction_GT$df[3] `, `r sum_Interaction_GT$df[2]`}$ = `r (sum_Interaction_GT$coefficients[4,3])`, _p_ = `r f_num(sum_Interaction_GT$coefficients[4,4], digits= 3)`). 

Planned contrasts showed that subjects believed positively valenced claims were significantly truer than negative valenced ones when the claims are targeted at their ingroup ($t_{`sum_Contrast1_GT$df[1]`}$ = `r (sum_Contrast1_GT$t.ratio[1])` , _p_ = `r f_num(sum_Contrast1_GT$p.value[1], digits= 3)`), but there were no differences between valences when the claims are targeted at their outgroup ($t_{`sum_Contrast1_GT$df[2]`}$ = `r (sum_Contrast1_GT$t.ratio[2])` , _p_ = `r f_num(sum_Contrast1_GT$p.value[2], digits= 3)`). Moreover, no differences were found between ingroupers and outgroupers on the the judgement of truth in the positive condition  ($t_{`sum_Contrast2_GT$df[1]`}$ = `r (sum_Contrast2_GT$t.ratio[1])` , _p_ = `r f_num(sum_Contrast2_GT$p.value[1], digits= 3)`) , and negative condition  ($t_{`sum_Contrast2_GT$df[2]`}$ = `r (sum_Contrast2_GT$t.ratio[2])` , _p_ = `r f_num(sum_Contrast2_GT$p.value[2], digits= 3)`) .
```






