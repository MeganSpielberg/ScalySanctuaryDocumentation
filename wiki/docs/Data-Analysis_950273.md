# Data Analysis

> ℹ️ **Note:** Author: Valentino

## 📊 Megan's Analysis (Control vs. Base Game vs. Hardcoded Vet)

Megan and Valentino each wrote a separate research paper for the
graduation project, analysing different condition pairings from the
same data collection. The slides below are **Megan's own analysis**,
comparing the Non-Game Control, Game/Base, and Game/Hardcoded-Vet
conditions. This is a separate, self-contained analysis with its own
sample size — the numbers in it will not match the rest of this page,
which documents Valentino's analysis below.

[Data Analysis Megan.pdf](images/950273/18645003.pdf)

Additional analysis document: [Data Analysis (1).pdf](images/950273/19333122.pdf)

## 📄 Overview

This document describes the statistical analyses conducted for
**Valentino's** research paper, examining knowledge acquisition and
engagement across three instructional conditions: the Game / Non-LLM
Interactive Condition (Version 1), the Game / LLM-Interactive Condition
(Version 3), and the Non-Game Control Condition (Version 4). For each
analysis, the rationale, SPSS procedure, and relevant output are
described.

> ℹ️ **Note:** All analyses were conducted in [IBM SPSS Statistics](SPSS_884737.md) following
> outlier exclusion. The final analytic sample consisted of 70
> participants: Version 1 (n = 23), Version 3 (n = 20), and Version 4
> (n = 27). Version 2 was excluded from all analyses.

## 🔎 Outlier Analysis

### 💡 Rationale

Prior to running inferential analyses, pre- and post-knowledge scores
were visually inspected for outliers using scatter plots. Outliers were
defined as data points sitting substantially outside the main
distribution. Two participants with pre-knowledge scores of 6.5-7 were
excluded, as was one participant with a post-knowledge score of 1. Case
filtering was applied in SPSS rather than permanent deletion to preserve
the original dataset.

### 💻 SPSS Procedure

| Step | Action |
|----|----|
| 1 | Create a case number variable: Transform → Compute Variable → Target Variable: case_number → Numeric Expression: $CASENUM → OK |
| 2 | Create scatter plot: Graphs → Chart Builder → Scatter/Dot → Simple Scatter → Y-axis: pre_knowledge_score → X-axis: case_number → OK |
| 3 | Repeat Step 2 for post_knowledge_score on the Y-axis |
| 4 | Identify outliers visually from the plots |
| 5 | Apply filter: Data → Select Cases → If condition is satisfied → If: pre_knowledge_score <= 6 AND post_knowledge_score >= 2 AND game_version <> 2 → Filter out unselected cases → OK |

## 📈 Mixed Factorial Repeated Measures ANOVA

### 💡 Rationale

A mixed factorial repeated measures ANOVA was conducted to examine
whether knowledge scores changed significantly from pre- to post-test
and whether this change differed across game conditions. The
within-subjects factor was time (pre-test, post-test) and the
between-subjects factor was game version (Version 1, 3, 4). This
approach models the temporal structure of the data, accounts for
individual baseline differences, and tests both the main effect of time
and the time x condition interaction within a single model.

### 💻 SPSS Procedure

| Step | Action |
|----|----|
| 1 | Navigate to: Analyze → General Linear Model → Repeated Measures |
| 2 | Within-Subject Factor Name: time → Number of Levels: 2 → click Add → click Define |
| 3 | Move pre_knowledge_score to slot 1 and post_knowledge_score to slot 2 under the within-subjects variable |
| 4 | Move game_version to the Between-Subjects Factor(s) box |
| 5 | Click Contrasts → select game_version → Contrast: Simple → Reference Category: Last → click Change → Continue |
| 6 | Click Post Hoc → move game_version to Post Hoc Tests → tick Bonferroni → Continue |
| 7 | Click Options → move all effects to Display Means for → tick Descriptive statistics, Estimates of effect size, Observed power → Continue |
| 8 | Click Plots → Horizontal Axis: time → Separate Lines: game_version → Add → Continue |
| 9 | Click OK to run the analysis |

### 📋 Key Output to Report

- From the Multivariate Tests table: report Pillai's Trace for the time
  effect and the time x condition interaction effect (F, df, p).

- From the Tests of Within-Subjects Effects table: report the
  Sphericity Assumed row for both time and time x condition (F, df, p).
  Mauchly's test confirmed sphericity (W = 1.000), so no correction was
  needed.

- From the Tests of Between-Subjects Effects table: report the version
  row (F, df, p) for the between-subjects main effect.

- From the Contrast Results (K Matrix): report the contrast estimate,
  standard error, and significance for each version compared to Version
  4 (reference).

- From the Post Hoc Multiple Comparisons table: report mean
  differences, standard errors, and Bonferroni-corrected p values for
  all pairwise comparisons.

### 📝 Results Summary

| Effect | Result |
|----|----|
| Time (main effect) | F(1, 67) = 151.846, p < .001 |
| Time x Condition (interaction) | F(2, 67) = 3.519, p = .035 |
| Between-subjects (Condition) | F(2, 67) = 1.213, p = .304 |
| Version 1 vs Version 4 (contrast) | Estimate = 0.485, p = .230 |
| Version 3 vs Version 4 (contrast) | Estimate = 0.588, p = .162 |
| Post hoc: all pairwise comparisons | All p > .05 after Bonferroni correction |

## 1️⃣ One-Way ANOVA: Engagement Score

### 💡 Rationale

A one-way between-subjects ANOVA was conducted to examine whether
engagement scores differed significantly across game conditions.
Engagement was measured once post-intervention using an adapted Game
Experience Questionnaire. Because engagement was not measured at
multiple time points, a repeated measures approach was not applicable.
Post hoc Bonferroni comparisons were used to identify which specific
condition pairs drove any significant overall effect.

### 💻 SPSS Procedure

| Step | Action |
|----|----|
| 1 | Navigate to: Analyze → General Linear Model → Univariate |
| 2 | Dependent Variable: engagement_score |
| 3 | Fixed Factor(s): game_version |
| 4 | Click Contrasts → select game_version → Contrast: Simple → Reference Category: Last → click Change → Continue |
| 5 | Click Post Hoc → move game_version across → tick Bonferroni → Continue |
| 6 | Click Options → move game_version to Display Means for → tick Descriptive statistics, Estimates of effect size → Continue |
| 7 | Click OK to run the analysis |

### 📋 Key Output to Report

- From the Tests of Between-Subjects Effects table: report the version
  row (F, df, p) and R Squared value.

- From the Contrast Results (K Matrix): report the contrast estimate,
  standard error, and significance for each version compared to Version
  4 (reference).

- From the Post Hoc Multiple Comparisons (Bonferroni) table: report
  mean differences, standard errors, and corrected p values for all
  pairwise comparisons.

### 📝 Results Summary

| Comparison | Result |
|----|----|
| Condition effect (overall) | F(2, 67) = 4.320, p = .017, R² = .114 |
| Version 1 vs Version 4 (contrast) | Estimate = 3.448, p = .052 |
| Version 3 vs Version 4 (contrast) | Estimate = 5.126, p = .006 |
| Post hoc: Version 1 vs Version 3 | Mean diff = -1.68, p = 1.000 |
| Post hoc: Version 1 vs Version 4 | Mean diff = 3.45, p = .157 |
| Post hoc: Version 3 vs Version 4 | Mean diff = 5.13, p = .019 * |

## 🔗 Pearson Correlation: Knowledge Gain and Engagement Score

### 💡 Rationale

A Pearson correlation was conducted to examine whether knowledge gain
and engagement score were related across all conditions. This tests
whether participants who learned more also tended to report higher
engagement, regardless of which condition they were assigned to.

### 💻 SPSS Procedure

| Step | Action |
|----|----|
| 1 | Navigate to: Analyze → Correlate → Bivariate |
| 2 | Move knowledge_gain and engagement_score to the Variables box |
| 3 | Under Correlation Coefficients: ensure Pearson is ticked |
| 4 | Test of Significance: Two-tailed |
| 5 | Tick Flag significant correlations |
| 6 | Click OK |

### 📝 Results Summary

| Variables | Result |
|----|----|
| Knowledge Gain vs Engagement Score | r = .249, p = .037, n = 70 |

## 🔗 Pearson Correlation: LLM Interactions and Knowledge Gain

### 💡 Rationale

A Pearson correlation was conducted within the Game / LLM-Interactive
Condition to examine whether the number of messages sent to the
veterinary NPC was associated with knowledge gain. LLM interaction
counts were derived from dialogue log data and merged with the main
dataset prior to analysis.

### 📃 Data Preparation

| Step | Action |
|----|----|
| 1 | Count player messages per participant from the dialogue logs using Python (see LLM_Condition_Data.csv) |
| 2 | Import LLM_Condition_Data.csv into SPSS: File → Import Data → CSV Data → follow import wizard → OK |
| 3 | Confirm llm_interactions and knowledge_gain variables are present |
| 4 | Apply filter to include only Version 3 cases if running from main dataset |

### 💻 SPSS Procedure

| Step | Action |
|----|----|
| 1 | Navigate to: Analyze → Correlate → Bivariate |
| 2 | Move llm_interactions and knowledge_gain to the Variables box |
| 3 | Under Correlation Coefficients: ensure Pearson is ticked |
| 4 | Test of Significance: Two-tailed |
| 5 | Tick Flag significant correlations |
| 6 | Click OK |

### 📝 Results Summary

| Variables | Result |
|----|----|
| LLM Interactions vs Knowledge Gain | r = .226, p = .338, n = 20 (non-significant) |

## 💬 LLM Dialogue Log Analysis

### 💡 Rationale

Descriptive analysis of the LLM dialogue logs was conducted to
characterise how participants in the Game / LLM-Interactive Condition
engaged with the veterinary NPC across game loops and modules. This
analysis was exploratory and descriptive in nature, examining total
message frequency, distribution across loops, and distribution across
game modules.

### 📁 Data Source

Dialogue logs were exported as LLMDialogueLogs_Blad1.csv. Each row
represented one interaction event, with columns for timestamp, user ID,
version, loop number, scene, trigger, and dialogue content. Player
messages were identified by rows beginning with 'Player:' and were
extracted and counted per participant using Python.

### 🔑 Key Descriptives

| Metric | Value |
|----|----|
| Total player messages | 201 |
| Mean messages per participant | 7.73 (SD = 5.33, range = 1-23) |
| Loop 1 messages | 79 (M = 3.29, SD = 2.03) |
| Loop 2 messages | 72 (M = 3.27, SD = 2.41) |
| Loop 3 messages | 50 (M = 2.63, SD = 1.98) |
| Feeding module messages | 118 (M = 4.54, SD = 2.55) |
| Terrarium Building module messages | 83 (M = 4.37, SD = 3.82) |

## ⭐ Main Conclusions

### 🧠 Knowledge Acquisition

All three conditions produced significant pre-to-post knowledge gains
(F(1, 67) = 151.846, p < .001). The magnitude of knowledge gain differed
significantly across conditions (F(2, 67) = 3.519, p = .035), with the
Game / Non-LLM Interactive Condition showing the highest mean gain
(M = 3.74, SD = 2.62), followed by the Game / LLM-Interactive Condition
(M = 3.25, SD = 1.94), and the Non-Game Control Condition showing the
lowest gain (M = 2.22, SD = 1.58). Pairwise post hoc Bonferroni
comparisons and simple contrasts did not identify significant
differences between any specific condition pairs (all p > .05), likely
reflecting insufficient statistical power given the group sizes of 20
to 27 participants per condition.

### ✨ Engagement

Game condition had a significant effect on engagement
(F(2, 67) = 4.320, p = .017, R² = .114). The Game / LLM-Interactive
Condition produced significantly higher engagement than the Non-Game
Control Condition (mean difference = 5.13, p = .019), confirmed by
simple contrasts (estimate = 5.126, p = .006). No significant
difference in engagement was found between the two game conditions
(p = 1.000).

### 🤝 Relationship Between Knowledge Gain and Engagement

A significant positive correlation was found between knowledge gain and
engagement across all conditions (r = .249, p = .037, n = 70),
indicating that participants who gained more knowledge also tended to
report higher engagement.

### 🤖 LLM Usage

LLM interaction frequency declined across game loops (Loop 1: n = 79;
Loop 2: n = 72; Loop 3: n = 50), suggesting decreasing reliance on the
NPC as gameplay progressed. No significant association was found
between LLM interaction frequency and knowledge gain (r = .226,
p = .338, n = 20).
